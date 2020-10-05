git clone http://github.com/jadyhome/terminal-git-practice

cd terminal-git-practice

git checkout -b develop

git checkout -b solutions

touch solutions.md

git add solutions.md

git commit -m "add solution file to save my commands"

code solutions.md

git add solutions.md   
git commit -m "add command to change path to home directory"

git push origin solutions

mkdir ~/ga
 
cd ga
mkdir week1 week2 week3 week4 week5 week6 week7 week8 week9 week10 week11 week12

cd testingfolder
cd terminal-git-practice
git add solutions.md
git commit -m "created ga in home directory and created 12 new directories within ga folder"
git push origin solutions

cd ~
cd ga
mkdir project1 project2 project3 project4
cd testingfolder
cd terminal-git-practice
git add solutions.md
git commit -m "created 4 project directories"
git push origin solutions