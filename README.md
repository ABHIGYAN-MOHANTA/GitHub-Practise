# Story2
Learning Git and Github
github practise

Dont create readme at the start

git init
git status
git add . (if you have added something in the staging area by mistake, you can remove them by: git rm --cached -r . )
git status
git commit
git log
repeat untill done
git diff to see changes
git checkout to revert bacck


git remote add origin <url>
//if remote already exists git remote remove origin

git push -u origin master
enter personal access tolen

.gitignore (just write the names of the files to be ignored like secrets.txt and .DS-Store but in separate lines. also use # for comments and * for ignoring all files for the same type{ like *txt will ignore all txt files})

git clone <url>

git branch <name of the branch> (to make a new branch)
git branch (to check all the existing branches, also asterisk * shows the current branch)
git checkout <name of branch> (to switch branch to new branch)
in this new branch make your changes 
if you are satisfied with your changes, switch back to main branch and
git merge <name of branch to be merged>

now to work on someone else' repo, fork it and work on it and then make a pull request
