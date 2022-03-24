GIT Commands learnt today

git remote -v 
lists local code

git remote add origin git@github.com:shreyasubramanya/helloworld.git 
the above step adds remote repository to your local machine

git fetch
fetches all the branches from remote to local

git checkout gireesh
local chooses gireesh branch to begin work


git pull origin main
bring in changes from remote main branch to local copy(origin)

git status
tells status of files in local directory


git add ./README.md
after changes made to add the file to list so we can coommit and push later


git commit -m "gireesh changes to the readme file"
commit the files and get ready to push, -m, adds comments


git push origin gireesh
pushes the committed files from origin(local) to remote gireesh branch

on github, raise a PR to merge main <--- gireesh



