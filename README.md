# Demo
Hello world this is my github testing.

## Generating ssh or deploy keys for a repository
 ssh-keygen -t rsa -b 4096 -C "mohsenzahab@github.com"

 ## git commands

### set default push branch for current branch 
    git push -u origin <branch name>
### list all branches
    git branch
### create or switch to a branch
    git checkout -b <branch name>
### deleting a branch
    git branch -d <name of the branch> 
### showing the differences between two branches
    git diff <other branch name>
### committing new changes not newly created files 
    git commit -am "message"
### merging
    git merge <branch name>
### resetting a change
    git reset <empty or file name>
### resetting last or further commit
    git reset HEAD<~<a number>>
    git reset HEAD~1
    git reset HEAD~2
### log your commits
    git log // you can reset(reset stages without saving change locally) from a certain point by using commit hash instead of HEAD
### completely undo change(stages + local)
    git reset --hard <hash or HEAD>

 ### Useful links
 https://gist.github.com/gubatron/d96594d982c5043be6d4

 new change on feature branch
 
