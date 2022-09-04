Bandit Level 3 → Level 4
Level Goal
The password for the next level is stored in a hidden file in the inhere directory.

    bandit3@bandit:~$ ls 
    inhere
    bandit3@bandit:~$ cd inhere/
    bandit3@bandit:~/inhere$ ls -la
    total 12
    drwxr-xr-x 2 root    root    4096 Sep  1 06:30 .
    drwxr-xr-x 3 root    root    4096 Sep  1 06:30 ..
    -rw-r----- 1 bandit4 bandit3   33 Sep  1 06:30 .hidden
    bandit3@bandit:~/inhere$ file .hidden
    .hidden: ASCII text
    bandit3@bandit:~/inhere$ cat .hidden
    2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
    bandit3@bandit:~/inhere$ exit
    logout
    Connection to bandit.labs.overthewire.org closed.