Bandit Level 4 → Level 5
Level Goal
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your 
terminal is messed up, try the “reset” command.

    bandit4@bandit:~$ ls
    inhere
    bandit4@bandit:~$ cd inhere/
    bandit4@bandit:~/inhere$ ls -la
    total 48
    drwxr-xr-x 2 root    root    4096 Sep  1 06:30 .
    drwxr-xr-x 3 root    root    4096 Sep  1 06:30 ..
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file00
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file01
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file02
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file03
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file04
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file05
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file06
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file07
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file08
    -rw-r----- 1 bandit5 bandit4   33 Sep  1 06:30 -file09
    bandit4@bandit:~/inhere$ file -file00
    file: Cannot open `ile00' (No such file or directory)
    bandit4@bandit:~/inhere$ file ./-file00
    ./-file00: OpenPGP Public Key
    bandit4@bandit:~/inhere$ file ./-file01
    ./-file01: data
    bandit4@bandit:~/inhere$ file ./-file02
    ./-file02: data
    bandit4@bandit:~/inhere$ file ./-file03
    ./-file03: data
    bandit4@bandit:~/inhere$ file ./-file04
    ./-file04: data
    bandit4@bandit:~/inhere$ file ./-file05
    ./-file05: data
    bandit4@bandit:~/inhere$ file ./-file06
    ./-file06: data
    bandit4@bandit:~/inhere$ file ./-file07
    ./-file07: ASCII text
    bandit4@bandit:~/inhere$ file ./-file08
    ./-file08: data
    bandit4@bandit:~/inhere$ file ./-file09
    ./-file09: data
    bandit4@bandit:~/inhere$ cat ./-file07
    lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
    bandit4@bandit:~/inhere$ exit
    logout
    Connection to bandit.labs.overthewire.org closed.