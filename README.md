First Configuration
----------git commands used in session-----

labsuser@ubuntu1804:~/handson-basic$ history
 git --version
 mkdir handson-basic
cd handson-basic/
ls -a
git init
echo "# handson-basic" >> README.md
echo "First Configuration" > README.md 
git add README.md 
git commit -am "First Commit"
git branch -help   ->-- for every shortcut
git branch -M main   --> Move/rename ur default branch to main
git status
git remote add origin https://github.com/knowledgeira/handson-basic.git
git push -u origin main
git config --global credential.helper store       ---> Store your username and password use helper store

