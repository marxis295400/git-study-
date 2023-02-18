# git-study-
学习知识内容


#1、启动新存储库并将其发布到 GitHub
create a new directory, and initialize it with git-specific functions
git init my-repo

//change into the `my-repo` directory
cd my-repo

//create the first file in the project
touch README.md

//git isn't aware of the file, stage it
git add README.md

//take a snapshot of the staging area
git commit -m "add README to initial commit"

//provide the path for the repository you created on github
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git  //需要未建立分支，需要将路经smaster到main

//git branch n -m master main

//push changes to github
git push --set-upstream origin main
