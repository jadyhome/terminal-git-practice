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
git add .
git commit -m "created ga folder in home directory"
git push origin solutions
 
cd ga
ga mkdir week1 week2 week3 week4 week5 week6 week7 week8 week9 week10 week11 week12
