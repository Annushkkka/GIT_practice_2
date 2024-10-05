# GIT_practice_2
Выполнение второй работы "Работа с Git в терминале"

Вставляю все команды, выполненные в рамках этой практики:

  1  mkdir my_project
  
  2  cd my_project
  
  3  git init
  
  4  git status
  
  5  touch main.py
  
  6  git status
  
  7  git add main.py
  
  8  git status
  
  9  git commit -m "Initial commit with main.py"
  
 10  echo 'print("Hello, world!")' > main.py
 
 11  git add main.py
 
 12  git commit -m "Add Hello World to main.py"
 
 13  echo 'print("Another change")' >> main.py
 
 14  git add main.py
 
 15  git commit -m "Update main.py with another change"
 
 16  git log
 
 17  git config --global alias.cm "commit -am"
 
 18  touch utils.py README.md
 
 19  git add .
 
 20  git commit -m "Add utils.py and README.md"
 
 21  python3 -m venv venv
 
 22  echo "__pycache__/" > .gitignore
 
 23  git status
 
 24  git add .gitignore
 
 25  git commit -m "Add .gitignore to ignore __pycache__"
 
 26  git branch test
 
 27  git checkout test
 
 28  git branch
 
 29  echo 'print("Test branch update")' >> main.py
 
 30  git add main.py
 
 31  git commit -m "Add test branch update to main.py"
 
 32  git checkout master
 
 33  git merge test
 
 34  git commit -m "Merge test branch"
 
 35  git tag -a v1.0 -m "Release version 1.0"
