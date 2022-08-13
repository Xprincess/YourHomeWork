# GIT Instruction
__*Instruction for me*__
* *git config --global user.name ""*
* *git config --global user.email ""*
* *git version* - check your current version /Проверить версию Гита
* *git init* - creates a new Git repository/ Создаем новый репозиторий
* *git add* - adds a change in the working directory to the staging area/ добавляет  в терминал текущее изменение
* *git commit* - captures a snapshot of the project's currently staged changes/ добавляет изменеие в репозиторий
* *git status* - displays the state of the working directory and the staging area/ Показывает статус рабочего состояния
* *git check out* - lets you navigate between the branches created by git branch/ Просмотр добавленных веток/коммитов

## Reminder!

1. After adding new info don't forget to save the file (Cmd+S)  
2. After you save the files you add the file.s
3. Create commit

**Instruction Branch**

* *git branch* - check existing branches
* *git branch <name>* - create a new branch
* *git merge <branch name>* -  merge 2 branches

**Seminar 3 - remote repository**
Create a remote repository in github

or create a new repository on the command line
echo "# Check" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Xprincess/Check.git
git push -u origin main

or push an existing repository from the command line
git remote add origin https://github.com/Xprincess/Check.git
git branch -M main
git push -u origin main


* *git push* - moves the changes (from the master branch) to remote repository
* *git pull* - get the changes from the remote repository to local


This line has been added from the local repository 
  
  This line has been added from the remoted repository

  This line has been added from the side branch