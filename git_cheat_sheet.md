# Create and connect a repository

1.  git init

2.  _Create github/gitlab project_

3.  add some file

4.  **git remote add origin (project-url)**

5.  **git push -u origin master**

# Main commands

## Basic file management

git status

- check current status

## Staging basics

git add (file-name)

- stage the file or the changes made to this file

git add .

- stage the changes made to all the files

## Commit basics

git commit

- prompt for a commit message then commit the staging changes

git commit -a

- prompt for a commit message then merge AND commit all changes (do not add new file)

git commit -m "(commit message)"

- allow to print the commit message between double quotes

## Distant repo management

git push

- push all the changes made in the local repo the the distant one

git pull

- pull all the changes made in the distant repo the the local one

## Versioning

git log

- print all past commits and their commit message

git log --oneline

- shorten the log

git log --graph

- add a graph view for the branches

## Branching

git branch

- list all the branches, active one has an asterisk

git branch (new-branch-name)

- add a new branch (new-branch-name)

git switch (branch-name)

- switch branch to (branch-name)

git checkout (branch-name)

- switch branch to (branch-name)

git checkout -b (new-branch-name)

- create and switch to (new-branch-name)

git merge (branch-name)

- try to merge the branch (branch-name)

git branch -d (branch-name)

- delete the branch (branch-name)