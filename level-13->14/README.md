 Level 13 → Level 14
 ssh bandit13@bandit.labs.overthewire.org -p 2220
 ls
 sshkey.private
 scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private ~/key14     //logs in using a private SSH key instead of password
 chmod 600 ~/key14
 ssh -i ~/key14 bandit14@bandit.labs.overthewire.org -p 2220
 cat /etc/bandit_pass/bandit14
 password of next level is displayed
