Bandit Level 0 → Level 1
Level Goal
The password for the next level is stored in a file called readme located in the home directory. 


    bandit0@bandit:~$ find readme
    readme
    bandit0@bandit:~$ cat readme
    NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
    bandit0@bandit:~$ exit
    logout
    Connection to bandit.labs.overthewire.org closed.

Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to 
log into that level and continue the game.
    
    ┌──(lazarot㉿kali)-[~]
    └─$ ssh bandit1@bandit.labs.overthewire.org  -p 2220                                                           
                             _                     _ _ _   
                            | |__   __ _ _ __   __| (_) |_ 
                            | '_ \ / _` | '_ \ / _` | | __|
                            | |_) | (_| | | | | (_| | | |_ 
                            |_.__/ \__,_|_| |_|\__,_|_|\__|
                                                           
    
                          This is an OverTheWire game server. 
                More information on http://www.overthewire.org/wargames
    
    bandit1@bandit.labs.overthewire.org's password: 
    Permission denied, please try again.
    bandit1@bandit.labs.overthewire.org's password: 
    
          ,----..            ,----,          .---.
         /   /   \         ,/   .`|         /. ./|
        /   .     :      ,`   .'  :     .--'.  ' ;
       .   /   ;.  \   ;    ;     /    /__./ \ : |
      .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
      ;   |  ; \ ; | |    :     | /___/ \ |    ' '
      |   :  | ; | ' ;    |.';  ; ;   \  \;      :
      .   |  ' ' ' : `----'  |  |  \   ;  `      |
      '   ;  \; /  |     '   :  ;   .   \    .\  ;
       \   \  ',  /      |   |  '    \   \   ' \ |
        ;   :    /       '   :  |     :   '  |--"
         \   \ .'        ;   |.'       \   \ ;
      www. `---` ver     '---' he       '---" ire.org
    
    
    Welcome to OverTheWire!
    
    If you find any problems, please report them to the #wargames channel on
    discord or IRC.
    
    --[ Playing the games ]--
    
      This machine might hold several wargames.
      If you are playing "somegame", then:
    
        * USERNAMES are somegame0, somegame1, ...
        * Most LEVELS are stored in /somegame/.
        * PASSWORDS for each level are stored in /etc/somegame_pass/.
    
      Write-access to homedirectories is disabled. It is advised to create a
      working directory with a hard-to-guess name in /tmp/.  You can use the
      command "mktemp -d" in order to generate a random and hard to guess
      directory in /tmp/.  Read-access to both /tmp/ is disabled and to /proc
      restricted so that users cannot snoop on eachother. Files and directories
      with easily guessable or short names will be periodically deleted! The /tmp
      directory is regularly wiped.
      Please play nice:
    
        * don't leave orphan processes running
        * don't leave exploit-files laying around
        * don't annoy other players
        * don't post passwords or spoilers
        * again, DONT POST SPOILERS!
          This includes writeups of your solution on your blog or website!
    
    --[ Tips ]--
    
      This machine has a 64bit processor and many security-features enabled
      by default, although ASLR has been switched off.  The following
      compiler flags might be interesting:
    
        -m32                    compile for 32bit
        -fno-stack-protector    disable ProPolice
        -Wl,-z,norelro          disable relro
    
      In addition, the execstack tool can be used to flag the stack as
      executable on ELF binaries.
    
      Finally, network-access is limited for most levels by a local
      firewall.
    
    --[ Tools ]--
    
     For your convenience we have installed a few useful tools which you can find
     in the following locations:
    
        * gef (https://github.com/hugsy/gef) in /opt/gef/
        * pwndbg (https://github.com/pwndbg/pwndbg) in /opt/pwndbg/
        * peda (https://github.com/longld/peda.git) in /opt/peda/
        * gdbinit (https://github.com/gdbinit/Gdbinit) in /opt/gdbinit/
        * pwntools (https://github.com/Gallopsled/pwntools)
        * radare2 (http://www.radare.org/)
    
     Both python2 and python3 are installed.
    
    --[ More information ]--
    
      For more information regarding individual wargames, visit
      http://www.overthewire.org/wargames/
    
      For support, questions or comments, contact us on discord or IRC.
    
      Enjoy your stay!
    
    bandit1@bandit:~$ 
