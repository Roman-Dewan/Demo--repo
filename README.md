# Demo--repo
this is my first git repository
# author - Md Roman Dewan

# Configuring Git config:<br>
    git config --global user.name "My Name"
    git config --global user.email "email@email.com"
    git config --list
    
# Clone and status<br>
    1. Cloning a repository on our local machine 
        git clone<-some link->
    2. status - display the state of the code.
       git status.
   
cd- change directory <br>
# Add and commit
    -> add - adds new or changed files in your working diretory to the    Git stagging area.
    -> git add<-file name->
    -> git add . (add all file in the folder)


# Commit- it is the record of change<br>
    git commit-m"some message"

# push- Upload local repo content to remote repo.<br>
    git push origin main
    git push -u origin main

# init command:<br>
    1. init used to create a new repo.
    2. get init.
    3. git remote origin main
    4. git remote -v (to verify remote)
    5. git branch (to chech branch)
    6. git branch -M main(to rename branch)
    7. git push origin main.
    8. # git push -u origin main.
# Branch Commands
    1. git branch (to chech branch)
    2. git branch -M main (to rename branch -> if we change the name of main , then the changes name will appear at branch name.)
    3. git checkout <-branch name->  (to navigate)
    4. git checkout -b <-new branch name-> (to create new branch)
    5. git branch -d <-branch name-> (to delete branch)