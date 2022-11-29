---
title: /
layout: home
permalink: /
---
# root@debian:~# <span style="color: black;">ls -al</span>

total 12
drwxr-xr-x 3 root root 4096 Nov 29 10:00 .
drwx------------------ 5 root root 4096 Nov 29 10:00 ..
drwxr-xr-x 3 root root 4096 Nov 29 10:00 hackintoanetwork
                                                                                                                                          
# root@debian:~# <span style="color: black;">cd ./hackintoanetwork && ls -al</span>

total 16
drwxr-xr-x 3 root root 4096 Nov 29 10:00 .
drwx------------------ 5 root root 4096 Nov 29 10:00 ..
drwxr-xr-x 2 root root 4096 Nov 29 10:00 blog
-rw-r------r------ 1 root root   55 Nov 29 10:00 hello

# root@debian:~/hackintoanetwork# <span style="color: black;">cat hello</span>

Hello I’m hackintoanetwork.
Web Hacker & CTF Player.

# root@debian:~/hackintoanetwork# <span style="color: black;">cd ./blog && ls</span>
