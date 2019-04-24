# Deadends of Information Technology

I was born 1976, learned programming 1989, studied information technology 1996-2001 and worked since then in this business.

I am 43 years old now. I have seen a lot of hypes coming and going.

Here is list of things I have seen going. Some former hypes, some things that never started. 

"All we are is dust in the wind" (Songwriter: Kerry Livgren)

GUI development: gtk and qt: http://sotagtrends.com/?tags=[gtk,qt]

## Network File Systems

NFS (Network File System). Application servers use storage servers using simple protocols like s3 to store and retrieve blobs.
And users prefer the speed of very fast local ssd disks. Software gets stored in git. Many documents get edited only, and the few bytes 
that get stored in your personal $HOME directory get synced with DropBox, Nextcloud or GoogleDrive.

Same for WebDAV. 
http://sotagtrends.com/?tags=[nfs,webdav]

Owncloud (ownCloud is a suite of client–server software for creating and using file hosting services. ownCloud functionally has similarities to the widely used Dropbox) was great some months ago. I switched to nextcloud like most other users:

http://sotagtrends.com/?tags=[owncloud,nextcloud]


# API and Data Exchange

## Corba

Corba was a big hype some years ago. AFAIK it does not get used for new projects any more.

Stateless APIs have won.

Corba gave you references to remote objects. Sounds great at the beginning. But stateless APIs (via http) are simpler. 
And simpler is better than "wow".

http://sotagtrends.com/?tags=[corba]

## SOAP

From Wikipedia: SOAP (abbreviation for Simple Object Access Protocol) is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. Its purpose is to provide extensibility, neutrality and independence. It uses XML Information Set for its message format, and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP) or Simple Mail Transfer Protocol (SMTP), for message negotiation and transmission. 

https://en.wikipedia.org/wiki/SOAP

Me: It is too complicated. It is overengineered. The client for python was not updated since months. Dead.

http://sotagtrends.com/?tags=[soap]

# Data formats

XML was a very big hype. Again: Way too complicated. Not simple enough. JSON (current hype) is much better to exchange data, since it supports some simple data types (int, string, list, dictionaries)

http://sotagtrends.com/?tags=[xml,json]


# Applications

Emacs: I used this text editor 14 years daily (2001-2015). I switched to PyCharm. http://sotagtrends.com/?tags=[emacs,pycharm]

zsh: Alternative to the bash shell (linux command line langauge). I was very interested at the beginning. But finally, you do not gain much. The bash is the default shell, and for me it does not make much sense to use a different shell. http://sotagtrends.com/?tags=[zsh,bash]

Alternative to the (source code) version-control system git. Git has won. Alternatives do not make sense any more. http://sotagtrends.com/?tags=[git,mercurial,bazaar,svn]

OpenStack: http://sotagtrends.com/?tags=[openstack]

Desktop office: MS-Office, Libreoffice. These programms were very important in the past. Today most people learned, that you can write the text directly into the mail body. You do not need to add a ms-word document to the mail. 
http://sotagtrends.com/?tags=[ms-office,libreoffice]

KDE "The K desktop environment" was very wide spread (at least in germany) for some years. But gnome has not much more traffic: http://sotagtrends.com/?tags=[kde,gnome]


# Programming languages

Low-level languages like assembly, C, C++ are the building blocks of higher level languages. But the usage of these languages is in decline or constant low. Here in comparison with Python: http://sotagtrends.com/?tags=[assembly,c,c%2B%2B,python]

Java was a big hype and is still wide spread. It is no "deadend" yet, but declining: http://sotagtrends.com/?tags=[python,java]

I just don't know if XSLT is a programming language or a data format. I never liked it. It was way too verbose, it was complicated to write. It was not a real programming language and simple things got complicated soon.
I am happy to see XLST going: http://sotagtrends.com/?tags=[xslt]

Perl vs Python: http://sotagtrends.com/?tags=[perl,python]

C# vs Ruby vs Python: http://sotagtrends.com/?tags=[c%23,python,ruby]

# Linux on the desktop.

Some overambitious friends of open source software and open data formats thought you need to switch from Microsoft Windows to Linux as soon as possible. Like the LiMux Project in the year 2005:

> LiMux was a project by the city of Munich in Germany to migrate local government software systems from closed-source, proprietary Microsoft products to free and open-source software. The project ran from 2005 to 2013, migrating over 18,000 personal computers and laptops of public employees to a Linux-based software solution.

See: https://en.wikipedia.org/wiki/LiMux

I think they did a major mistake: It would have been much simpler, and more successfull, if they would have done several small steps, instead of one big step. First step for me would be to switch from closed source to open source application, but stay on MS-Windows operating system. The LiMux project wanted too much too soon (Linux on the desktop). The LiMux project failed.

https://en.wikipedia.org/wiki/LiMux

Today, every desktop usage is decreasing. Mobile interfaces get used.

# Hardware

Ubuntu-Phone. Don't ask me why Mark Shuttleworth ever thought this will be a success. https://en.wikipedia.org/wiki/Ubuntu_Touch

# Configuration Management

Chef and Puppet (the older ones) and Ansible and Salt where the new ones. In 2013 it was not clear who will win the race. Today in 2019 it is clear. Ansible has won: http://sotagtrends.com/?tags=[salt-stack,ansible,chef,puppet]

# Backup

Of course making backup of data is still done often and makes sense. But it gets done less often.

mobile devices: My wife, my son and I wo do not backup our mobile phones. I guess most people do it like this. The device does not store important data that is not stored somewhere else. The device contains contacts, calendars, some documents shared via nextcloud. Mails are stored on the mail server. 

At work I do no backup of linux laptop. Software I write gets pushed to a central server every day.

See the trend: http://sotagtrends.com/?tags=[backup]

# Mailing lists

I the past I used mailing lists a lot. But today I use StackOverflow and other sites from StackExchange. And a few google groups. I am only subscribed to a few mailing lists today.


# Markup Languages

I think markup languages have lost - except html. Once upon a time Markup languages like  reStructuredText were used to create documentation
which can be compiled to HTML or PDF. Who prints docs today? I don't know anybody who prints docs today.

HTML is the future. There are easy to use HTML online editors like CKEditor. 

HTML gives two distinct groups of people all that they want. Geeks can write HTML directly and use all feature it offers. And CKEditor gives non-geeks a way to create formated text.

Markup languages are on the downward trend.

Most of them go down. Markdown still goes a bit up: http://sotagtrends.com/?tags=[sphinx,restructuredtext,markdown,mediawiki]

Same for Latex. The need for printable documentation is falling.

# Inotify

Inotify is a nice feature of the linux kernel. You can listen for changes in directories. If there is a change (for example a new file), then
you get an event and you can execute some custom code (for example process the new file).

I once thought inotify is great. 

Time has changed.

Now I know: the file system is not an API.

Today I prefer http.

# Mail admin - a declining job

Decision-makers prefer to pay for service offered by big well-known giants. They do not like to pay a human which does the job.

This google trend chars shows it: Microsoft-Exchange (mail server for windows) and Postfix (mail server for linux) are in decline. Configuring mail servers is not easy. Especially handling spam is daily work and annoyance. If you are young and you are unsure what you want to do in the future? Do not consider to get a mail admin. This job is in decline:

https://trends.google.com/trends/explore?date=all&q=%2Fm%2F02js54,%2Fm%2F04nh2c

People do not use native GUI mail user agents (like for example thunderbird) less. They use the web interface of big mail providers more.

Maybe this trend is good. I had to explain the difference between an envelope-from to the body-from already several times to people who were responsible for a mail server. This difference seems to be too much for the average windows admin. See: https://en.wikipedia.org/wiki/Bounce_address


# microkernel

In the year 2000 when I was a student (HTW Dresden) I was very curious about
micro kernels. At TU-Dresden there were projects working on a micro kernel based
operating system. I loved to talk with people involved in the micro kernel projects.
But I found no answer to the question "why?" which convinced me. In the year 2000
I thought to myself "I don't get why a microkernel should be better than a modular
kernel like linux".

Now, in the year 2019 I think there are no real arguments pro microkernel. Nice theory, but performance is much more important. And practical real world applications of several operating systems today. Fault toleranz gets handled at a differen level today.




