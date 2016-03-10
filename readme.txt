echo "# test1" >> README.md  id:wang7651 pw:1qazxsw2
git init
git add readme.txt
git commit -m "first commit"
git remote add origin https://github.com/wang7651/test1.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/wang7651/test1.git
git push -u origin master