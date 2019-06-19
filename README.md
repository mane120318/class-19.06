## To push a new project to github

1. make a github repository
2. (WINDOWS) open git bash in your folder
  a) Open folder with file explorer
  b) git bash here
3. git init
4. git add { filename }
  _git add index.html style.css_
5. git commit -m "Msg"
  _git commit -m "add index.html and style.css"_
6. git remote add origin { your repo link here }
  _git remote add origin git@github.com:istc-accelerator-5/class-19.06.git_
7. git push origin master

*. git status
  Shows the current status

## To push new commits to an existing repo

1. Change files
2. git add { filename }
  _git add README.md_
3. git commit -m "Msg"
  _git commit -m "Add pushing new commits to existing repo steps"_
4. git push origin master

## To clone a repository

1. Copy the link from remote repo
2. git clone { repo link }
 _git clone git@github.com:istc-accelerator-5/class-19.06.git_