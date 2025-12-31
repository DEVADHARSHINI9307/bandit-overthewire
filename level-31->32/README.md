Level 31 → Level 32
// username: bandit31
ssh bandit31@bandit.labs.overthewire.org -p 2220

// enter password for level 31

git clone ssh://bandit31-git@localhost/home/bandit31-git/repo
cd repo                                                                          //clones the repository

echo "May I come in?" > key.txt                //creates required file with exact content

git add key.txt
git commit -m "add key"
git push

///adds file, commits it, and pushes to server

exit

password of next level (bandit32) is displayed
