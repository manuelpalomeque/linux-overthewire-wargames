Bandit Level 9 → Level 10
Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, 
preceded by several ‘=’ characters.


    bandit9@bandit:~$ file data.txt 
    data.txt: data
    bandit9@bandit:~$ strings data.txt | grep  "^==" 
    ========== the
    ========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
    bandit9@bandit:~$ 
