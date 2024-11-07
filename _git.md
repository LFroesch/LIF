# Git Quick Start

echo "# Project Name" >> README.md

echo "# To Do" >> todo.md

git init

echo "todo.md" >> .gitignore

git add *

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/UserName/Project.git

git push -u origin main