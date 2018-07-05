# MyCloud
Personal Cloud for [MyDroid](https://github.com/varasys/MyDroid) mobile OS

MyCloud is a personal cloud meant to completely replace iCloud, google cloud, samsung cloud, etc.

The main purpose is to centralize all user data in one location fully controlled by the user; and specifically to minimize switching costs to prevent vendor lock-in to mediocre and predatory corporate products.

The concept is to use [ArchLinux](https://www.archlinux.org/) on a [ZFS](http://www.open-zfs.org/wiki/Main_Page) root filesystem installed on an individuals Virtual Private Server ([VPS](https://en.wikipedia.org/wiki/Virtual_private_server)). This work has already started and is available at [paczfs](https://github.com/varasys/paczfs).

Fundamentally, it is just a file server and some services such as a web server, smtp server, etc. with tight permissions based on the Identity Transfer Protocol - Secure ([ITPS](https://github.com/varasys/ITPS)) protocal.

MyCloud will act as a users "hub" for all their digital devices, and will have negligable switching costs to move to another VPS, and to back-up all data to a hard drive at the users home (for double backup and safe keeping).

As a "hub" MyCloud will also facilitate Tor style obfuscation, and Torrent style data sharing.

Users MyCloud's can be linked (using tokens) so items posted on one users MyCloud can be fetched by another users MyCloud and show up in their "feed".

So basically, it is a combination Facebook-like service, cloud service, VPN service with 100% backup and disaster recovery based on a secure network protocol.

## Team Skills Needed
1. Linux Developers
2. ArchLinux Specialists (assuming ArchLinux base)
3. Specialists for each server component (web server (nginx?), email, etc.)
