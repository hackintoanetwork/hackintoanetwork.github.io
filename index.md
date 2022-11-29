---
title: /
layout: home
permalink: /
---
# root@debian:~# ls -al

total 52
drwx------  5 root root  4096 Nov 29 10:37 .
drwxr-xr-x 18 root root  4096 Nov 22 13:31 ..
-rw-------  1 root root  6691 Nov 29 02:04 .bash_history
-rw-r--r--  1 root root   571 Apr 10  2021 .bashrc
drwxr-xr-x  4 root root  4096 Nov 18 13:31 .cache
drwx------  3 root root  4096 Nov 23 00:32 .config
-rw-r--r--  1 root root   161 Jul  9  2019 .profile
-rw-------  1 root root 14306 Nov 29 10:37 .viminfo
drwxr-xr-x  3 root root  4096 Nov 29 10:37 hackintoanetwork
                                                                                                                                          
# root@debian:~# cd ./hackintoanetwork && ls -al

total 16
drwxr-xr-x 3 root root 4096 Nov 29 10:37 .
drwx------ 5 root root 4096 Nov 29 10:37 ..
drwxr-xr-x 2 root root 4096 Nov 29 10:36 blog
-rw-r--r-- 1 root root   55 Nov 29 10:37 hello

# root@debian:~/hackintoanetwork# cat hello

Hello I’m hackintoanetwork.
Web Hacker & CTF Player.

# root@debian:~/hackintoanetwork# cd ./blog && ls
