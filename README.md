# git-commands
# input-forms

git init

git add .

git commit -m "Add existing project files to Git"

git remote add origin https://github.com/cameronmcnz/example-website.git

git push -u -f origin master


If the problem is "main and master are entirely different commit histories.", the following will work

git checkout master   
git branch main master -f    
git checkout main  
git push origin main -f 

How to Fix the error: failed to push some refs to Error in Git
We can fix the error: failed to push some refs to [remote repo] error in Git using the  git pull origin [branch] or git pull --rebase origin [branch] commands. In most cases, the latter fixes the error

…or push an existing repository from the command line

git remote add origin https://github.com/CypherAk007/git-commands.git

git branch -M main

git push -u origin main
