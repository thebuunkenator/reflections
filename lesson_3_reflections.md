# Lesson 3

### creating repository on github

- create repository on github (+) sign
- add repo as a remote to the repo on your computer
- git remote # see all the current remotes
- add repo: git remote add <name> # meestal origin:
	`git remote add origin https://github.com/thebuunkenator/reflections.git`

`> git remote -v`

`origin	 https://github.com/thebuunkenator/reflections.git (fetch)`

`origin	 https://github.com/thebuunkenator/reflections.git (push)`


`> git push origin master # arg1: remote you want to push changes to, #arg2 local branch you like to push`




### When would you want to use a remote repository rather than keeping all your work local?
- when you are not on your own computer
- when you don't need to do something with your files (compile f.e.)
- when other people need to see changes immediately

When you made changes remote (or someone else has made changes) you need to update your local repository:

`git pull origin master` 

![image](img/Screenshot 2014-12-30 22.20.20.png)

### Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?

- you never know what has been changed, and don't know if you're code is still working. You first need to check this
- changes are difficult to be undone
- You might need to merge branches
- Maybe you work on another branch 



