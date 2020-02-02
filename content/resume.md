---
title: "Resume"
date: 2019-02-08T14:52:07+01:00
categories:
tags:
keywords:
- about
comments:       false
showMeta:       false
showActions:    false

---
#### José Manuel Reyes

Paris, France  
Phone: +33 7 68 48 65 86  
E-mail: josereyesch [ at ] gmail

##### Summary

I'm a cross-functional Software Engineer with 10+ years' experience, passionate about cloud architectures and distributed systems.

##### Work Experience

**Full Stack Developer** *[Hilti](https://hilti.com), Paris, France (Jan 2020 - present)*

**Research and Development Engineer** *[Telecom SudParis](https://www.telecom-sudparis.eu/en/), Evry, France (Apr 2018 - Nov 2019)*

* Implemented a framework to identify the operational data-paths in Software Defined Networking (SDN) driven data plane. Given framework is based on distributed test case generation and monitoring. Five different tools (or modules) were developed, those are: (i) the extraction tool - a network packet sniffer written in Go and based on [GoPacket](https://github.com/google/gopacket) library, which is installed at all network interfaces of the data-plane forwarding devices, that forwards the traffic to the analyzer tool, (ii) the packet generation tool - a raw packet generator also written in Go, which is installed at all hosts in the data-plane, that generates packets with specific headers (in the widespread [pcap-filter](http://biot.com/capstats/bpf.html) syntax), (iii) the analyzer tool - a tool installed at the processing server that receives the packets, filters the packets having the same UID and computes the flow trees from the set of observations, (iv) the orchestration tool - receives the traffic of interest to generate, requests the packet generation tool to send a network packet with the requested headers using a specific UID, and finally (v) the User Interface(UI) tool - a web interface for discovering the data-paths that receives the interesting traffic to discover from the user and reports the resulting data-paths..
`Go` `Python` `bash` `MongoDB` `Docker` `SDN Controller`

**Senior Software Engineer** *[Smartmatic](https://smartmatic.com), Panama City, Panama (Nov 2016 - Mar 2018)*

* Designed and developed features for the US Election Management System which prepares the electoral data and configuration files for voting devices.

**Software Engineer** *[Smartmatic](https://smartmatic.com), Panama City, Panama, (Oct 2012 - Oct 2016)*

* Developed a canvassing system for the [Philippines 2016 General Election](https://www.smartmatic.com/case-studies/article/the-philippines-2016-general-election/) that expected votes from 92K vote counting machines and 55 million voters, deployed in 1.7K canvassing centers.
`JavaEE` `Bash` `Jboss` `Oracle` `Docker` `AngularJS`

* Reworked application that posts election returns on the web in near real-time, by synchronizing the generated results with Amazon EC2, resulting in ~15x generation speed improvement.
`JavaEE` `Jboss` `Oracle` `AngularJS` `AWS`

* Conducted source code review with technical committees of political parties and election watchers.

* Refactored Java Swing application that generates data files for voting machines used by 3 million voters in 2014 [Belgian elections](https://www.smartmatic.com/case-studies/article/belgian-elections-2012-2014/) deployed in 3.3k polling places.
`JavaEE` `Jboss` `PostgreSQL` `Custom Debian`
 

**Web Developer** *[FOX International Channels](http://foxinternational.com), Guatemala City, Guatemala (Sep 2009 - May 2012)*

* Implemented global publishing platform focused on creating and maintaining TV Channels Websites and TV Shows, helping to reduce custom setup and maintenance costs up to ~40%. 
`C#` `.NET` `SQL Server` `Umbraco` `Windows Server` `Brightcove API`

* Improved existing websites performance by integrating content distribution networks and compression/caching mechanisms, resulting in ~20x (from 1min to 3s) speed improvement.
`C#` `SQL Server` `HTML/CSS`

**Web Developer** *Ebclosion, Guatemala City, Guatemala (Apr 2008 - Sept 2009)*

* Designed and developed an RESTful API which provided authorization services to clients that needed SMS and WAP Push notification requests, used by 1000+ mobile campaigns through North, Central and South America Telecoms.
`Linux` `Apache` `MySQL` `Symfony`

**Systems Analyst and Programmer** *LN Comunicaciones S.A, Guatemala City, Guatemala. (Jul 2007-Mar 2008)*

* Developed a billing system to manage and control customers balances, assigning direct inward dial (DID) numbers using SOAP Web Services to process payments, used by 300+ customer service representatives.
`Linux` `Apache` `MySQL` `PHP` `Java`

##### Education

* **M.Sc. Information Technologies with specialization in Computer Networks & Information Security** *Galileo University, Guatemala City, Guatemala (2010)*

* **B.Sc. Systems, Informatics, and Computer Science Engineering** *Galileo University, Guatemala City, Guatemala (2007)*

##### Publications

* **José Reyes**, Jorge López, Natalia Kushik, Djamal Zeghlache: [On the Assessment and Debugging of QoE in SDN (work-in-progress paper)](https://ieeexplore.ieee.org/document/8935029) In Proceedings of the 18th IEEE International Symposium on Network Computing and Applications (NCA 2019), *Cambridge, MA, USA, Sept. 2019*

* **José Reyes**, Jorge López, Djamal Zeghlache: [Identifying Running Data-paths in SoftwareDefined Networking Driven Data-planes](https://ieeexplore.ieee.org/document/8935031) In Proceedings of the 18th IEEE International Sym-posium on Network Computing and Applications (NCA 2019), *Cambridge, MA, USA, Sept. 2019*

##### Skills

* Programming: `Java` `Go` `JavaScript(AngularJS, jQuery)` `C#(.NET)`,`PHP`, `Bash`
* Databases: `Oracle` `MySQL` `PostgreSQL` `SQL Server` `MongoDB`
* Development: `Agile(Scrum)` `Test driven development (acceptance/unit/integration)` `git` `SVN`
* Systems: `Unix/Linux` `Windows` `OSX` `Docker`
* Java Technologies: `Java EE` `JBoss` `WildFly` `Hibernate` `jOOQ` `JDBC` `JUnit` `Mockito` `Maven` `Spring` `ActiveMQ`
* Tools: `IntelliJ` `VS Code` `JIRA` `Bitbucket` `Jenkins`

##### Languages

* Spanish: Native
* English: Proficient User (C1)
* French:  Basic User (A2)

You can download a PDF version  [here](/assets/Jose_Reyes_CV.pdf).
