Bandit Level 6 → Level 7
Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

    bandit6@bandit:~$ cd /
    bandit6@bandit:/$ ls
    bin   dev  home     lib    lib64   lost+found  mnt  proc  run   snap  sys  usr
    boot  etc  krypton  lib32  libx32  media       opt  root  sbin  srv   tmp  var
    bandit6@bandit:/$ find -size 33c -and -user bandit7 -and -group bandit6
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-ModemManager.service-iSfqNM’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-systemd-resolved.service-FLUeCd’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-chrony.service-kntLU2’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-systemd-logind.service-YsYyqe’: Permission denied
    find: ‘./var/snap/lxd/common/lxd’: Permission denied
    find: ‘./var/lib/amazon’: Permission denied
    find: ‘./var/lib/chrony’: Permission denied
    find: ‘./var/lib/private’: Permission denied
    find: ‘./var/lib/udisks2’: Permission denied
    find: ‘./var/lib/snapd/void’: Permission denied
    find: ‘./var/lib/snapd/cookie’: Permission denied
    find: ‘./var/lib/ubuntu-advantage/private’: Permission denied
    find: ‘./var/lib/update-notifier/package-data-downloads/partial’: Permission denied
    find: ‘./var/lib/apt/lists/partial’: Permission denied
    ./var/lib/dpkg/info/bandit7.password

otro camino:

    bandit6@bandit:/$ id bandit7
    uid=11007(bandit7) gid=11007(bandit7) groups=11007(bandit7)
    bandit6@bandit:/$ id bandit6
    uid=11006(bandit6) gid=11006(bandit6) groups=11006(bandit6)
    bandit6@bandit:/$ find -size 33c -and -user 11007 -and -group 11006
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-ModemManager.service-iSfqNM’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-systemd-resolved.service-FLUeCd’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-chrony.service-kntLU2’: Permission denied
    find: ‘./var/tmp/systemd-private-43504cc0fc4c4ffa82cf4ad089249f2a-systemd-logind.service-YsYyqe’: Permission denied
    find: ‘./var/snap/lxd/common/lxd’: Permission denied
    find: ‘./var/lib/amazon’: Permission denied
    find: ‘./var/lib/chrony’: Permission denied
    find: ‘./var/lib/private’: Permission denied
    find: ‘./var/lib/udisks2’: Permission denied
    find: ‘./var/lib/snapd/void’: Permission denied
    find: ‘./var/lib/snapd/cookie’: Permission denied
    find: ‘./var/lib/ubuntu-advantage/private’: Permission denied
    find: ‘./var/lib/update-notifier/package-data-downloads/partial’: Permission denied
    find: ‘./var/lib/apt/lists/partial’: Permission denied
    ./var/lib/dpkg/info/bandit7.password
    bandit6@bandit:/$ cat ./var/lib/dpkg/info/bandit7.password
    z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

solucion mas eficaz:

    bandit6@bandit:/$ find -size 33c -user 11007 -group 11006 2>/dev/null
    ./var/lib/dpkg/info/bandit7.password
    bandit6@bandit:/$ cat ./var/lib/dpkg/info/bandit7.password
    z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
    bandit6@bandit:/$ 
