Bandit Level 1 → Level 2
Level Goal
The password for the next level is stored in a file called - located in the home directory

    bandit1@bandit:~$ ls -al
    total 24
    -rw-r-----  1 bandit2 bandit1   33 Sep  1 06:30 -
    drwxr-xr-x  2 root    root    4096 Sep  1 06:30 .
    drwxr-xr-x 49 root    root    4096 Sep  1 06:30 ..
    -rw-r--r--  1 root    root     220 Jan  6  2022 .bash_logout
    -rw-r--r--  1 root    root    3771 Jan  6  2022 .bashrc
    -rw-r--r--  1 root    root     807 Jan  6  2022 .profile
    bandit1@bandit:~$ cat ./-
    rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
    bandit1@bandit:~$ exit
    logout
    Connection to bandit.labs.overthewire.org closed.

