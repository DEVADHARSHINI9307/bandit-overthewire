// username: bandit16
ssh bandit16@bandit.labs.overthewire.org -p 2220

// enter password for level 16

nmap localhost -p 31000-32000               //scans ports from 31000 to 32000

//finds which ports are open and using SSL

openssl s_client -connect localhost:<open_port>        //connects to the correct SSL-enabled port

//the service outputs a private SSH key


chmod 600 sshkey.private           //sets correct permissions for the SSH private key


ssh -i sshkey.private bandit17@localhost -p 2220              //logs in as bandit17 using the private key


exit
password of next level (bandit17) is displayed
