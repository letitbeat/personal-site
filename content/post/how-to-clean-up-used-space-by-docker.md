---
title: "How to Clean Up Used Space by Docker"
date: 2017-02-25T17:22:14+01:00
categories:
tags:
- docker
- how to
keywords:
- tech
- docker
thumbnailImage: https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2017/11/06110003/docker.png
---
Using Docker has become very handy to must of us when working with multiple environments. However, one problem that we noticed is the incredible disk usage of it. So in this post I will list useful commands that could help us solving the issue.
<!--more-->

First, you must check and remove stopped Docker containers that will no longer be used.

To list this you can run:

```bash
   docker ps -a
```

After selecting the unused containers, you can remove them with the following command:

```bash
   docker rm -v {name or hexadecimal container identifier}
```

{{< alert info >}}
  The flag -v is used to also delete any associated volume.
{{</ alert >}}

Then, following command should be executed

* To delete "dead" containers. (containers with status=dead whose creation failed):

```bash
   docker ps -f status=dead --format '{{ .ID }}' | xargs -r docker rm -v
```

* To delete volumes not associated with any containers ( This usually happens when container are deleted without -v flag of docker rm command):

```bash
docker volume ls -qf dangling=true | xargs -r docker volume rm
```

* To delete images not longer referenced by any tag (`<none>`):

```bash
docker images --digests --format '{{.Repository}}:{{.Tag}}@{{.Digest}}' | sed -ne 's/:<none>@/@/p' | xargs -r docker rmi
```

* To delete images not longer referenced by any name:

```bash
docker images -qf dangling=true | xargs -r docker rmi
```

* To delete temporary files (blobs which were left by some interrupted docker pull):

```bash
rm -f /var/lib/docker/tmp/*
```

{{< alert warning >}}
Note: This files are useful in case we want to resume the docker pull command.
{{< /alert >}}

Hope you find this post useful and keep Dockering!
