# Deadends of Information Technology

I was born in 1976, learned programming 1989, studied information technology 1996-2001, and worked since then in this business.

I am 43 years old now. I have seen a lot of hypes coming and going.

Here is a list of things I have seen going. Some former hypes, some things that never started. 

"All we are is dust in the wind" (Songwriter: Kerry Livgren)

Most things I list below to get used daily by a lot of people and are mature solutions. But I won't go this way if I could start from scratch.

## Native GUI development

GUI development: gtk and qt: http://sotagtrends.com/?tags=[gtk,qt]

## Network File Systems

NFS (Network File System). Today people either use https://en.wikipedia.org/wiki/Server_Message_Block to access files on a network share, or they use a web-based file service (DropBox, Google Drive, Microsoft OneDrive, Nextcloud, ...)

Today application servers talk to storage servers using simple protocols like s3 to store and retrieve blobs, not NFS.


Same for WebDAV. 
http://sotagtrends.com/?tags=[nfs,webdav]

## OwnCloud
Owncloud (ownCloud is a suite of client-server software for creating and using file hosting services. ownCloud functionally has similarities to the widely used Dropbox) was great some months ago. I switched to Nextcloud like most other users:

http://sotagtrends.com/?tags=[owncloud,nextcloud]


# API and Data Exchange

## Corba

[Common Object Request Broker Architecture (CORBA)](https://en.wikipedia.org/wiki/Common_Object_Request_Broker_Architecture) was a big hype some years ago. In 2001 I thought this is the future. AFAIK it does not get used for new projects anymore.

Stateless APIs have won.

Corba gave you references to remote objects. Sounds great at the beginning. But stateless APIs (via HTTP) are simpler. 
And simpler is better than "wow".

http://sotagtrends.com/?tags=[corba,protocol-buffers]

## Microsoft COM

[Microsoft COM (Component Object Model)](https://en.wikipedia.org/wiki/Component_Object_Model)

It is very uncommon to automate MS-Word or Excel via COM these days. I am happy.

## SOAP, WSDL

From Wikipedia: SOAP (abbreviation for Simple Object Access Protocol) is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. Its purpose is to provide extensibility, neutrality, and independence. It uses XML Information Set for its message format and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP) or Simple Mail Transfer Protocol (SMTP), for message negotiation and transmission. 

https://en.wikipedia.org/wiki/SOAP

Me: It is too complicated. It is overengineered. The client for python was not updated for months. Dead.

XML-RPC was nice, too. Simpler than soap. But same here: dead.

WSDL: The Web Services Description Language is an XML-based interface description language that is used for describing the functionality offered by a web service.

http://sotagtrends.com/?tags=[soap,xml-rpc,wsdl]


# Data formats

## XML
XML was a very big hype. Again: Way too complicated. Not simple enough. JSON (current hype) is much better to exchange data since it supports some simple data types (int, string, list, dictionaries)

http://sotagtrends.com/?tags=[xml,json]

BUT: Binary data, native time format, time delta, and other things are missing. I think protocol-buffers would be great for exchanging data between systems, but up to now, only a few people think like this.

## latin1, windows-cp-1252 ...

Unicode has won. I am very happy. Poor guys who still need to fiddle with old character codes.

# Applications

Emacs: I used this text editor 14 years daily (2001-2015). I switched to PyCharm. http://sotagtrends.com/?tags=[emacs,pycharm]

zsh: Alternative to the bash shell (Linux command line language). I was very interested in the beginning. But finally, you do not gain much. The bash is the default shell, and for me, it does not make much sense to use a different shell. http://sotagtrends.com/?tags=[zsh,bash]

Alternative to the (source code) version-control system git. Git has won. Alternatives do not make sense anymore. http://sotagtrends.com/?tags=[git,mercurial,bazaar,svn]


Desktop office: MS-Office, Libreoffice. These programs were very important in the past. Today most people learned, that you can write the text directly into the mail body. You do not need to add an ms-word document to the mail. 
http://sotagtrends.com/?tags=[ms-office,libreoffice]

KDE "The K desktop environment" was very widespread (at least in Germany) for some years. But gnome has not much more traffic: http://sotagtrends.com/?tags=[kde,gnome]

Nagios was once the number 1 monitoring solution. Time has changed. I guess most people would not start to use it today if they could start from scratch. Here Nagios compared with Zabbix, PRTG, check_mk: https://trends.google.com/trends/explore?date=all&q=nagios,%2Fm%2F03c9jx,%2Fg%2F11bc5wdh4r,%2Fm%2F0h_9jxz .... or [Prometheus](https://prometheus.io/) from the CNCF.

# Cloud computing / Virtualization

## XEN

[XEN](https://en.wikipedia.org/wiki/Xen) (Linux Hypervisor). XEN compared with VMWare and Kubernetes: [Google Trend XEN, VMWare, Kubernetes](https://trends.google.de/trends/explore?date=all&q=%2Fm%2F02t3gg,%2Fm%2F01t9k5,%2Fg%2F11b7lxp79d)

## Vagrant

[Vagrant](https://en.wikipedia.org/wiki/Vagrant_(software)) gets used much less these days. See [Google trend vagrant](https://trends.google.com/trends/explore?date=all&q=%2Fm%2F0jwtqm2)

# Architecture (Web)

## LAMP Stack
Linux, Apache, MySQL, Perl/Python: http://sotagtrends.com/?tags=[jamstack,lamp]

JAMStack is coming?


# Programming languages

Low-level languages like assembly, C, C++ are the building blocks of higher-level languages. But the usage of these languages is in decline or constant low. Here in comparison with Python: http://sotagtrends.com/?tags=[assembly,c,c%2B%2B,python]. Nobody wants to call `malloc()` and `free()` any more.

Java was a big hype and is still widespread. It is no "dead-end" yet, but declining: http://sotagtrends.com/?tags=[python,java] In 2003 I was seeking a new job in a new city (Chemnitz). Most jobs for software developers were for Java or C/C++ developers. But I found a company where I can use Python daily ([tbz-pariv](http://www.tbz-pariv.de/))

I just don't know if XSLT is a programming language or a data format. I never liked it. It was way too verbose, it was complicated to write. It was not a real programming language and simple things got complicated soon.
I am happy to see XSLT going: http://sotagtrends.com/?tags=[xslt]

Perl vs Python: http://sotagtrends.com/?tags=[perl,python]

C# vs Ruby vs Python: http://sotagtrends.com/?tags=[c%23,python,ruby]

Shell Scripts: https://trends.google.de/trends/explore?date=all&q=shell%20scripts (I use the shell interactively daily. But I stopped
writing shell scripts several years ago. Either the script is important (then I would do it with Python and store it in git) xor it is unimportant.

# One Spec, several Implementations

C, C++, Java Enterprise Edition, and a lot of other development tools used the pattern "one specification, several implementations". I think this pattern is outdated. Modern tools (Python, TypeScript, Kubernetes, Go, Rust, Linux, ...) implement what's useful. No need to do this twice.

In the year 2000, I asked on one of the many apache java mailing lists about a new feature/idea. The response of the developers (roughly): "Yes, it would be nice to have this feature. But first, we need to wait for the new specification to get published.". This was one of the reasons I switched from Java to Python.

The pattern "One spec, several implementations" is useful for protocols like http/imap/smtp/snmp... and data formats (XML, json, YAML), but not for tools.

At least for Java Enterprise Edition and Enterprise Beans, the trend looks black: https://trends.google.com/trends/explore?date=all&q=%2Fm%2F0bs6x,%2Fm%2F0br1c

In 2019 Internet-Explorer switched to use the chrome engine. I guess Firefox will do the same sooner or later. Maybe there will be only one engine in some years.

[Business Process Execution Language](https://en.wikipedia.org/wiki/Business_Process_Execution_Language) was a standard executable language for specifying actions within business processes (aka workflows). Dead: [Trends of "BPEL"](https://trends.google.com/trends/explore?date=all&q=BPEL)

# Regular Expressions

Parsing text with regular expressions is like eating rubbish. In the 21 century, we send and receive data structures. We don't send strings that the receiver needs to parse.

https://trends.google.com/trends/explore?cat=32&date=all&q=regular%20expressions,json

# sed, awk, grep, ....

Parsing text with $YOUR_FAVORITE_TOOL is like eating rubbish.

I still use these tools sometimes interactively, but I don't write shell scripts anymore.

# Browser war

[Browser war](https://en.wikipedia.org/wiki/Browser_wars) Chrome has won.

# Linux on the desktop.

Some overambitious friends of open source software and open data formats thought you need to switch from Microsoft Windows to Linux as soon as possible. Like the LiMux Project in the year 2005:

> LiMux was a project by the city of Munich in Germany to migrate local government software systems from closed-source, proprietary Microsoft products to free and open-source software. The project ran from 2005 to 2013, migrating over 18,000 personal computers and laptops of public employees to a Linux-based software solution.

See: https://en.wikipedia.org/wiki/LiMux

I think they did a major mistake: It would have been much simpler, and more successful, if they would have done several small steps, instead of one big step. The first step for me would be to switch from closed source to open source application but stay on the MS-Windows operating system. The LiMux project wanted too much too soon (Linux on the desktop). The LiMux project failed.

https://en.wikipedia.org/wiki/LiMux

Today, every desktop usage is decreasing. Mobile interfaces get used.

And if you use a desktop you use the browser for most tasks. Software as a service eats the native GUI.

# Hardware

Ubuntu-Phone. Don't ask me why Mark Shuttleworth ever thought this will be a success. https://en.wikipedia.org/wiki/Ubuntu_Touch

# Configuration Management

Chef and Puppet (the older ones) and Ansible and Salt are the new ones. In 2013 it was not clear who will win the race. Today in 2019 it is clear. Ansible has won: http://sotagtrends.com/?tags=[salt-stack,ansible,chef,puppet]

# Backup

Of course, making a backup of data is still done often and makes sense. But it gets done less often.

mobile devices: My wife, my son, and I, do not backup our mobile phones. I guess most people do it like this. The device does not store important data that is not stored somewhere else. The device contains contacts, calendars, some documents shared via Nextcloud. Mails are stored on the mail server. 

Of course, it will be very annoying if the mobile device would get lost or broken. It will be a lot of work to configure the new device. But no important data would get lost.

At work, I do no backup of the Linux laptop. Software I write gets pushed to a central git server every day.

See the trend: http://sotagtrends.com/?tags=[backup]

# Perfect Filesystems

Several times the perfect Linux filesystem was invented: ext2, ext3, reiserfs, zfs, btrfs .... 

Today the discussions about which file system is the best have mostly vanished.

I could not find a reliable reference, but AFAIK google used ext2 for their servers very long (If you find a reliable reference, please tell me). To make it short: It does not matter. If you want high availability, then be sure that your service survives the outage of servers. A reliable file system does not make your whole service reliable.

Modern applications use storage services.

# Communication

Roughly until 2004 I used [Usenet](https://en.wikipedia.org/wiki/Usenet). Which was replaced by [mailing lists](https://en.wikipedia.org/wiki/Mailing_list)

But today I use StackOverflow, other sites from StackExchange, Reddit and Facebook Groups. Github issues get used to ask questions, too.

I like this change. This buries the never-ending discussion if the reply on a mailing-list should go to the list or to the author of the mail. 

# Markup Languages

I think markup languages have lost - except HTML and markdown. Once upon a time, Markup languages like SGML, XML, reStructuredText .. were used to create documentation
that can be compiled to HTML or PDF. Who prints docs today?

HTML is the future. Easy to use HTML WYSIWYG editors exist. See my list of [WYSIWYG editors](https://github.com/guettli/wysiwyg)

HTML gives two distinct groups of people all that they want. Geeks can write HTML directly and use all the features it offers. And WYSIWYG editors give non-geeks a way to create formatted text.

Other markup languages are on a downward trend.

Most of them go down. Markdown goes up, since it is convenient for simple formatting like Github README files: http://sotagtrends.com/?tags=[sphinx,restructuredtext,markdown,mediawiki]

Same for Latex. The need for printable documentation is falling. In 2001 I used Latex for my diploma thesis. This was a good choice since MS-Word and OpenOffice were not reliable these days. Today, I think I would not use Latex again.

Some for [DocBook](https://en.wikipedia.org/wiki/DocBook). See [google trend "DocBook"](https://trends.google.de/trends/explore?date=all&q=%2Fm%2F0c1gr). I am so happy to see this down-trend.

# Inotify

Inotify is a nice feature of the Linux kernel. You can listen for changes in directories. If there is a change (for example a new file), then
you get an event and you can execute some custom code (for example process the new file).

I once thought inotify is great. 

Time has changed.

Now I know: the file system is not an API.

Use Case: a third-party service sends you pairs of files. One image file and one json file. The json file contains meta-information. If you receive the files via SMB/NFS/FTP and trigger the handling of these files via inotify, then you can't reject broken data. Imagine you get only the json file, but not the image file. Now you (the receiver) need to handle this broken data. If you use HTTP, you can reject broken data and the issue is left to the sending party. And that's where the issue should be. The receiver can't fix broken data. It the job of the sender to transfer valid data.

Of course, the above use case applies if you don't use inotify. You could use a cronjob which imports the files every five minutes.

Today I prefer HTTP.

Shameless plug: You can use [tbzuploader](https://github.com/tbz-pariv/tbzuploader) to upload single or pairs of files via HTTP.

# Mail admin - a declining job

Decision-makers prefer to pay for service offered by big well-known giants. They do not like to pay a human which does the job.

This google trend-charts shows it: Microsoft-Exchange (mail server for windows) and Postfix (mail server for Linux) are in decline. Configuring mail servers is not easy. Especially handling spam is daily work and annoyance. If you are young and you are unsure what you want to do in the future? Do not consider to get a mail admin. This job is in decline:

https://trends.google.com/trends/explore?date=all&q=%2Fm%2F02js54,%2Fm%2F04nh2c

People do use native GUI mail user agents (like for example thunderbird) less often. They use the web interface of big mail providers more.

Maybe this trend is good. I had to explain the difference between an envelope-from to the body-from already several times to people who were responsible for a mail server. This difference seems to be too much for the average windows admin. See: https://en.wikipedia.org/wiki/Bounce_address

But today handling mail is more than managing an SMTP and IMAP server. For most users mail, spam filtering, calendar, contacts, sending and accepting invitations via mail, cloud storage and ... all is one thing.

Who influences the future of (mail) admins? The people how to pay them. And most decision-makers prefer to pay for a service that has reliable support even on weekends. The admin wants a weekend and he wants a holiday and sometimes he is ill. Be honest with yourself: If you would be the decision-maker, it is sad but true, you would choose the service, not the human.

And that's why I think in the future there will be fewer (mail) admins. Companies with less than 200 accounts will buy a service. Only big companies will run their own infrastructure. 

Of course, there needs to someone for the hardware. But the server hardware will leave the small companies, moving to big companies providing cheap software as a service. No need to care for backup, too. Doesn't this feel like flying?


Sooner or later automation will eat all jobs.

# microkernel

In the year 2000 when I was a student (HTW Dresden), I was very curious about
microkernels. At TU-Dresden projects were working on a micro-kernel-based
operating system. I loved to talk with people involved in the micro kernel projects.
But I found no answer to the question "why?" which convinced me. In the year 2000
I thought to myself "I don't get why a microkernel should be better than a modular
kernel like Linux".

Now, in the year 2019, I think there are no real arguments pro microkernel. Nice theory, but performance is much more important. Practical real-world applications use several operating systems today. Fault tolerance gets handled at a different level today.

But there are micro-kernel-based operating systems like: https://genode.org/

# RAW photo format

When I bought my first reflex camera (Canon 50D) most friends who already had a reflex camera told me that it is great because you can make photos in the raw image format. This raw format contains much more information and this is much, much better for post-processing.

I still like my reflex camera (it is ten years old now), but I never liked the raw format. Yes, the post-processing possibilities are great. But the size is a major drawback. And the time you need to do the post-processing.

I asked some of my friends some days ago again. None of them still use the raw image format by default today. They all use jpeg. It is simpler, more convenient.

Of course, some professional photographers use the raw format daily. That's not what I talk about. I look at the everyday use case of an average human who likes to take pictures.

# DRBD

> DRBD is a distributed replicated storage system for the Linux platform. It is implemented as a kernel driver, several userspace management applications, and some shell scripts. DRBD is traditionally used in high availability (HA) computer clusters, but beginning with DRBD version 9, it can also be used to create larger software-defined storage pools with a focus on cloud integration.

Source: https://en.wikipedia.org/wiki/Distributed_Replicated_Block_Device

DRBD is not dead, but it does decline.

The High availability method "One master, N secondary slaves" with failover was popular in the past.

Today High availability get's handled differently.


The trends show how it does decline. Here in comparison with [Ceph](https://en.wikipedia.org/wiki/Ceph_%28software%29): https://trends.google.com/trends/explore?date=all&q=%2Fm%2F0b1yt5,ceph


# Web Development 

Java Applets running in the web browser are dead: https://trends.google.com/trends/explore?date=all&q=java%20applets

Same for Adobe Flash Player: https://trends.google.com/trends/explore?date=all&q=%2Fm%2F05qh6g

In the year 2001, when I finished my studies, I never thought the trend will be like this. In the beginning, the language JavaScript was not taken seriously. Today JavaScript is even running on the server.

Up to now (2019) I still use jQuery. But I was told by several JavaScript developers, that if you start from scratch today, you don't need jquery and more. The tag trend is clear: http://sotagtrends.com/?tags=[jquery]

Synthetic JavaScript benchmarks don't make sense. See why octane was retired: https://v8.dev/blog/retiring-octane

# Internet

## FTP

If you still use FTP consider using [tbzuploader](https://github.com/tbz-pariv/tbzuploader) which is a generic upload tool for HTTP. Of course, the server needs to support this. But this very simple: Just return "201 created" if the upload was successful.

## Mirrors

In the past, it was common to run a script that detects which mirror is the best for your particular internet connection. Of course, debian/ubuntu packages and other stuff still gets mirrored. But in most cases, it is not needed anymore.



# Jenkins

It is still actively used. But the future looks black - GitLab is coming: http://sotagtrends.com/?tags=[jenkins,gitlab]

# Portability

In a world of containers and SaaS, you don't need portability anymore. You create software that takes a vanilla Linux distribution container image. Then you modify this according to your needs. There is no need to support several operating systems. If your application wants to use database FooDB (in my case PostgreSQL), then use all features FooDB supports. Often (not always) you don't need to support several different databases.

Of course, this does not apply to all software. General-purpose things like compilers (gcc), interpreters (Python), databases (PostgreSQL), IDE (PyCharm), web-browsers ... still need to be portable. But only a few developers spent their time building these fundamental building blocks.

"Portable shell scripts?" ... HELP! Don't waste your time writing portable shell scripts.

Portability across different browsers? The situations can't be compared to the past. Today you use a library like jquery, React or Angular and only rough edge cases are not portable.

Look at all the confusion and useless work that was created by thinking writing a bash script is evil. The term "Bashism" was created and over-committed people started to make things more complicated instead of easier. See https://wiki.ubuntu.com/DashAsBinSh Depending on my mood this makes me laugh or sometimes cry. The DashAsBinSh page contains so many things to consider. But according to my point of view, the most important thing is missing. The "why?" is missing. I see no real reason, no measurable benefit. If you want to use the bash use "#!/bin/bash" at the top and make the rpm/dpkg depend on the bash. If you want to use a super-fast-shell, then use "#!/bin/super-fast-shell" at the top and make the rpm/dpkg depend on the super-fast-shell. Why try to write a script which runs with bash and super-fast-shell? Compare this to python/perl: Have you ever considered to write a script which can be executed by the Perl and by the python interpreter :-) ?

# Skolelinux (and other custom Linux distributions)

> Skolelinux/Debian-Edu is a Linux distribution intended for educational use and a Debian Pure Blend. The free and open source software project was founded in Norway in 2001 and is now being internationally developed.

Sometimes specific solutions are better, sometimes general solutions are better.

I think this is a very good example of "learning from the past".

Supporting the existing project seems much slower in the beginning and people think "let's build something new for our use case". What happens when the initial enthusiasm settles? In this case, the solution was not specific for schools. A reliable and simple to set up Linux server has many use cases. It is better to join forces instead of trying to build something new.

Skolinux advertises with:

> server, desktops, thin clients - everything out of the box
> free, but behind the scenes with commercial and professional support
> 100% free software - ready to use for every kind of network
> complety compatible to microsoft-windows-clients

My dentist has the same needs. An architecture office, too. Charitable institutions for the care of neglected orphans.... The headquarter of the Worldwide Evil Hedge Fond ... all need reliable servers, desktops and thin clients. 

So why a new **distribution**? Everybody should have his custom Linux distribution? This makes no sense.

Why not support an existing Linux distribution and provide some additional applications on top?

Same for [Debian Med](https://en.wikipedia.org/wiki/Debian_Pure_Blend#Debian-Med)

> The Debian Med project is a Debian Pure Blend created to provide a co-ordinated operating system and collection of 
> available free software packages that are well-suited for the requirements for medical practices and medical research.

Sounds good. Sounds like [the practice of charity](https://en.wikipedia.org/wiki/Charity_(practice). Charity gives you and me a warm feeling inside. 

It is discriminating. Why invest time and money into a custom Linux distribution if only a few people benefit from it? It feels less like charity, but in reality, it is more generosity if you help to develop something generic which helps everybody.

But how to provide useful service to help people? You need to lower the barrier. Installing a Linux distribution is a lot of effort. You won't reach many people. An application that works on Windows, Linux, and Mac will reach more people. An application which just requires a web browser reaches nearly everybody.

# LAN, LDAP and VPN

VPNs are still wide-spread. You can't see a down trend in the [Google Trend for VPN, LDAP, Active Directory](https://trends.google.com/trends/explore?date=all&q=%2Fm%2F012t0g,%2Fm%2F04plq,%2Fm%2F011bm). This is a guess that LAN, LDAP, VPNs etc will get used less often in the future.

https exists. Why a second security layer? Of course there are a lot of use-cases where you need more than one layer. 
But for most cases https is enough.

If you don't need a network drive any more (since you use GSuite, Office 365 or Nextcloud), then it is likely that you don't need a VPN any more. Leaving a very skinny almost serverless LAN.

The future is "Sign in with [Google|Facebook|Microsoft|...]" via [OpenID Connect](https://en.wikipedia.org/wiki/OpenID_Connect)

And since https gets used, and not http, it does not make sense to have a Proxy in the LAN. Of course on the server-side software like [HAProxy](https://en.wikipedia.org/wiki/HAProxy) makes sense.

# Download

Today, you hardly download anymore. See [Google Trend for "Download"](https://trends.google.com/trends/explore?date=all&geo=US&q=download,%2Fm%2F0bm3b)

# Epilogue

You use some tools or methods which are dated? No need to follow every hype, but you would never do this again if you could start from scratch.

Lesson learned: The [Bandwagon effect](https://en.wikipedia.org/wiki/Bandwagon_effect) eats diversity. [The winner takes it all](https://www.youtube.com/watch?v=92cwKCU8Z5c)
