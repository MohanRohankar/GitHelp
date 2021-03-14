# GitHelp

User manual for vcs, git, github &amp; gitlab.

…or create a new repository on the command line

echo "# Java-Projects" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/MohanRohankar/Java-Projects.git

git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/MohanRohankar/Java-Projects.git

git branch -M main

git push -u origin main


//////////////////////////////////////


 Git Commands :
 
 0.  git --version 
 1.  git config --global user.email "your@mail.id"
 2.  git config --global user.name "yourUsername"
 3.  git config --list
 4.  git init | ( for git repo initialization )
 5.  git add * | ( '*' must be replaced with '.' for adding all files to loacl repo or must be replaced with 'filename' to add specific file to local repo)
 6.  git commit -m | "informative message for commit" ( commit changes with message )
 7.  git remote add origin "repo url" |  ( need to add for first time in order to specify local and remote url as one )
 8.  git push -u origin master | (push all the changes to remote repo )
 9.  git status
 10. git pull ( to recieve all the changes at remote )
 11. git checkout "branch name" ( to check and work under a specific branch )
 12. git clone "git_repo_url" (to create copy of remote in your local)
  
