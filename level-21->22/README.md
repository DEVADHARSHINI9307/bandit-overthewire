Bandit Level 21 → Level 22
// username: bandit21
ssh bandit21@bandit.labs.overthewire.org -p 2220

// enter password for level 21

ls /etc/cron.d/          //lists cron job configuration files

cat /etc/cron.d/cronjob_bandit22              //reads the cron job to understand what script runs automatically

cat /usr/bin/cronjob_bandit22.sh               //displays the script executed by cron , script shows where the password is written         

cat /tmp/t7O6lds*                   //reads the temporary file created by the cron job

exit
password of next level (bandit22) is displayed
