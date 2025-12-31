Level 22 → Level 23
// username: bandit22
ssh bandit22@bandit.labs.overthewire.org -p 2220

// enter password for level 22

cat /etc/cron.d/cronjob_bandit23          //shows the cron job for bandit23

cat /usr/bin/cronjob_bandit23.sh           //displays the script logic

echo I am user bandit23 | md5sum              //generates the same hash used in the script

cat /tmp/<generated_hash>                     //reads the file created using the hash name

exit


password of next level (bandit23) is displayed
