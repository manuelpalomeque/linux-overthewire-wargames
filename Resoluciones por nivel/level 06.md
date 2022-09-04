Bandit Level 5 → Level 6
Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following 
properties:

human-readable
1033 bytes in size
not executable

    bandit5@bandit:~/inhere$ find -size -1034c -and  -size +1032c
    ./maybehere07/.file2
    bandit5@bandit:~/inhere$ file ./maybehere07/.file2 
    ./maybehere07/.file2: ASCII text, with very long lines (1000)
    bandit5@bandit:~/inhere$ cat ./maybehere07/.file2
    P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
    bandit5@bandit:~/inhere$ exit
    logout
    Connection to bandit.labs.overthewire.org closed.
