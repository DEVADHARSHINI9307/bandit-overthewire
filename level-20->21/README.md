Level 20 → Level 21
// username: bandit20
ssh bandit20@bandit.labs.overthewire.org -p 2220

// enter password for level 20

ls             //lists files in the home directory   ,shows a file named suconnect

nc -l 1234          //opens a listening network port (port 1234)

  waits to receive data from another program

➡ keep this terminal open

./suconnect 1234               //runs the suconnect program

sends the current password to the listening port

➡ the program returns the password for the next level

exit

password of next level (bandit21) is displayed
