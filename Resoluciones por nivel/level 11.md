Bandit Level 10 → Level 11
Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data

    bandit10@bandit:~$ file data.txt 
    data.txt: ASCII text
    bandit10@bandit:~$ cat data.txt 
    VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg==
    bandit10@bandit:~$ base64 -d data.txt 
    The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
