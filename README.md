# sysadmin-resources
Here you will find a curated collection of links to aid the weary SysAdmin. I will try and categorize these sanely, and updates will continue through time.

## Table of Contents

1. [System Management](#system-management)
2. [Networking](#networking)
3. [Databases](#databases)
4. [Logs](#logs)
5. [Security](#security)
6. [Virtualization](#virtualization)
7. [Misc.](#misc)

## System Management
+ [Linux Insides](https://0xax.gitbooks.io/linux-insides/) - A great free online book to help understand the linux kernel, boot process, and other low-level happenings.

+ [Signal(7) man-page](http://man7.org/linux/man-pages/man7/signal.7.html) - Useful guide for sending proper signals during proc management

+ [systemd for Administrators](https://gist.github.com/bcremer/8cdf6900c35dda65f387) - Collection of the series of posts on 0xpointer dot net, its very useful for in-depth understanding of the newer init system

+ [Demystifying systemd](https://people.redhat.com/bbreard/presos/Demystifying_systemd_Summit_2020.pdf) - Red Hat Summit 2020 presentation slides going over some important functions and features of `systemd` in <45min.

+ [Chmod codes cheat sheet](https://gist.github.com/juanarbol/c44e736be70279c1fd5d68aa24f9d8be) - For when you forget about how octal notation and applying specific files/folder permissions works!

+ [Devops Cheatsheet](https://rubytune.com/cheat/) - Handy list of terminal commands for daily administration

+ [Strace -- The Sysadmin's Microscope](https://blogs.oracle.com/linux/strace-the-sysadmins-microscope-v2) - Introduction to using the system-call tracer `strace` for low-level troubleshooting

+ [pure bash bible](https://github.com/dylanaraps/pure-bash-bible) - Many methods of system tasks without dependencies by solely using bash.

+ [Gentoo Linux amd64 Handbook: Installing Gentoo](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation) - You don't have to install Gentoo to gain some nice low-level details and perspective on things like the linux kernel, sources, partition schemes, filesystems, and other system details. Very helpful for a fresh linux sysadmin.

+ [Linux From Scratch](http://www.linuxfromscratch.org/lfs/downloads/stable/) - The official directory containing the latest "stable" version of the Linux From Scratch .pdf. For taking a deep dive into how a linux system _really_ works from the inside-out.

+ [The Linux Kernel](https://archive.ph/WKpj3) - "Some remarks on the Linux Kernel" (although that's not giving this compendium enough credit, imo)

+ [A Beginner's Guide to Salt](https://www.linode.com/docs/guides/beginners-guide-to-salt/) - Tutorial for using [`Salt`](https://www.saltstack.com/) as a system provisioning and maintenance/configuration management tool. Includes a lot of good documentation links to get up and running with.

+ [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite) - Ever-useful suite of utilities for performing maintenance and troubleshooting on Windows systems.

+ [Understanding Numbers in PowerShell](https://devblogs.microsoft.com/scripting/understanding-numbers-in-powershell/) - A Windows DevBlog article including a very helpful table of numbers types in PowerShell and their limitations.

+ [Unix System Monitoring and Diagnostic CLI Tools](https://docs.monadical.com/s/system-monitoring-tools) - "An opinionated list of CLI utilities for monitoring and inspecting Linux/BSD systems." - more than enough tools to take a look at for nix admin tasks, as well as examples provided for each one.

## Networking
+ [Diagnosing a Slow Network](https://alta3.com/blog/diagnosing-a-slow-network) - Doing greuling network testing using "..three tools that a system admin should routinely use: `mtr`, `iperf`, and MTU testing with `ping`."
 
+ [How to SSH Properly](https://gravitational.com/blog/how-to-ssh-properly/) - Looking on a good start into getting ssh up and running client and/or server side? Here is a good source for that.

+ [iptables ArchWiki](https://wiki.archlinux.org/index.php/Iptables) - The arch linux wiki entry for iptables, which seems to cover the utility thoroughly and provides examples/scenarios

+ [Tor is a Great SysAdmin Tool](https://www.jamieweb.net/blog/tor-is-a-great-sysadmin-tool/)  A good blog post on using [Tor](https://www.torproject.org/) for things like testing and troubleshooting with networks.

## Databases
+ [SQL Quick Reference](https://www.w3schools.com/SQL/sql_quickref.asp) - a short 'cheat sheet' for SQL commands by W3Schools

+ [Windows - SQL Server technical documentation](https://docs.microsoft.com/en-us/sql/sql-server/?view=sqlallproducts-allversions) - The "motherlode" reference for any Windows SQl Server details.

## Logs
+ [OWASP page - Log review and management](https://www.owasp.org/index.php/Log_review_and_management) - A nice set of guidlines from OWASP on generally handling and maintaining logs. Includes some nice links at the bottom too.

+ [Syslog : The Complete System Administrator Guide](https://devconnected.com/syslog-the-complete-system-administrator-guide/) - A pretty comprehensive guide to the Linux Syslog protocol

## Security
+ [Basic Linux Privilege Escalation](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/) - Small guide that serves as a tutorial of testing a system to gain elevated access. A Windows equivalent of this guide can be found [here](https://www.absolomb.com/2018-01-26-Windows-Privilege-Escalation-Guide/)

+ [OpenBSD's AFTERBOOT(8) manual page](https://man.openbsd.org/afterboot) - While this is specific to the OpenBSD OS, it should serve as a handy "priority" post-install config guide for system administration of Unix/Linux systems across the board

+ [Basic and advanced configuration of Security-Enhanced Linux (SELinux)](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/selinux_users_and_administrators_guide/index) - RHEL's guide for SElinux configuration and management, including sections for basics as well as more in-depth coverage of the access control system

+ [An Overview of Cryptography](https://www.garykessler.net/library/crypto.html) - A very long and thorough "book" highlighting the principles and details of several crypto protocols/systems. Lots of math and links.

+ [DigiCert SSL Certificate Installation Instructions & Tutorials](https://www.digicert.com/kb/ssl-certificate-installation.htm) - Some guides to installing SSL/TLS certs (several platforms and OS tutorials). Yes, this is DigiCert's own knowledge base articles, but ti should serve as basics for other CAs as well

+ [Common Vulnerability Scoring System Calculator ](https://nvd.nist.gov/vuln-metrics/cvss/v2-calculator) - NIST's Common Vulnerability Scoring System (CVSS) "calc", useful for prioritizing the severity of known vulnerabilities on systems and building a case(s) for patching/acting accordingly. 

+ [systemd service sandboxing and security hardening 101](https://www.ctrl.blog/entry/systemd-service-hardening.html) - A blog post run-down on how to handle security configs within systemd.

+ [the cryptopals crypto challenges](https://www.cryptopals.com/) - "This is a different way to learn about crypto than taking a class or reading a book. We give you problems to solve. They're derived from weaknesses in real-world systems and modern cryptographic constructions."

+ [Hacksplaining](https://www.hacksplaining.com/lessons) - A very nice visual run-through of common vulnerabilities with services to look out for (and some ways to prevent them)

## Virtualization
+ [docker for Beginners](https://docker-curriculum.com/) - Decent tutorial for getting started with docker and container configuration/management

+ [FreeBSD Jails Admin](https://www.freebsd.org/doc/handbook/jails.html) - Official FreeBSD introduction and further documentation on FreeBSD Jails for reasonably-secure virtualization.

## Misc.
+ [Enable Sysadmin](https://www.redhat.com/sysadmin/) - Red Hat Enterprise Linux's "community publication" for SysAdmins, featuring articles, tutorials, etc. A nice page to check on from time to time.

+ [CyberChef, The Cyber Swiss Army Knife](https://gchq.github.io/CyberChef/) - Decode Base64, convert date/time strings, decrypt/disassemble shellcode, and over 250 other operations available from this helpful webpage.

+ [Systems Administration for Cyborgs](http://cyborginstitute.org/projects/administration/) - A _very_ nice series of short guides/introductions to SysAdmin principles and duties, including tools and best practices. Serves as a good intro to Linux SysAdmin work in general.

+ [Servers For Hackers](https://serversforhackers.com/) - Mostly hands-on guides and video tutorials for server configuration and management. Many posts are free, but there is a premium group of tutorials as well.

+ [Linux System Administrator/DevOps Interview Questions](https://github.com/chassing/linux-sysadmin-interview-questions) - Collection of interview questions for SysAdmin applicants - seems useful for preparation

+ [endoflife.date](https://endoflife.date/) - "This site maintains quick links for checking End Of Life dates for various tools and technologies."

+ [Regex For Noobs (like me!) - An Illustrated Guide](https://www.janmeppe.com/blog/regex-for-noobs/) - Gentle guide to using regular expressions (with illustrations, like it says)

+ [PowerShell equivalents for common Linux/bash commands](https://mathieubuisson.github.io/powershell-linux-bash/) - Transitioning from bash to Powershell (or visa-versa) can be somehwat jarring, and this guide might serve as a helping hand.

+ ["This is what I tell people to do.."](https://www.reddit.com/r/linuxadmin/comments/2s924h/how_did_you_get_your_start/cnnw1ma/) - an intensive skill-testing build/config to-do given as a response to an question on how someone could get started with understanding linux system admin work (based on an old version of CentOS but still applicable as far as I can see.)

+ [Sysadmin Casts](https://sysadmincasts.com/) - "Simple bite-sized DevOps Screencasts (released weekly)" <I don't think this is maintained anymore, though.>

+ ["Is Your Internet Up To Date?"](https://internet.nl/) - Silly domain name, but good site for birds-eye testing if "..your website, email and internet connection use modern and reliable Internet Standards.." and what actions you mihgt want to take if not.

+ [The myth of Sisyphus, and other essays](https://www2.hawaii.edu/~freeman/courses/phil360/16.%20Myth%20of%20Sisyphus.pdf) - ...a half-jest
