hello-world
#####################################################################
My first repository on GitHub

I am doing a course on coursera, 
where the usage of GitHub is recommended.

#####################################################################
Git Data Transport:
TO:
Workspace -[add]-> index -[commit]-> local repo -[push]-> remote repo

1) Adding to index: files are tracked
git add . : add all new files in wd
git add -u : update files (changes, deletes)
git add -A : update all

2) Committing: Save as an intermediate version on local repo!
git commit -m "description of what are the changes"

3) Put all changes on GitHub:
git push

4) Create new branch - for independent changes
git checkout -b branchname : create new development branch
git branch : which branch are you in
git checkout master : go back to master

5) Pull request (after pushing) - after forking someone's repo or if you have multiple branches: merge back
--> only GitHub, work online ("compare a pull request")

FROM:
remote repo -[fetch]-> local repo -[diff] [checkout]-> workspace
