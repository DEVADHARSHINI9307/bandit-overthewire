Level 6 → Level 7
ssh bandit6@bandit.labs.overthewire.org -p 2220

find / -user bandit7 -group bandit6 -size 33c 2>/dev/null     //searches entire system for file owned by bandit7, group bandit6, size 33 bytes,hides permission errors

cat /var/lib/dpkg/info/bandit7.password    //reads the password file

password of next level is displayed
