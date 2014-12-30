# Lesson 3

## creating repository on github

- create repository on github (+) sign
- add repo as a remote to the repo on your computer
- git remote # see all the current remotes
- add repo: git remote add <name> # meestal origin:
	git remote add origin https://github.com/thebuunkenator/reflections.git

	erik@Firefly ~/Documents/Computer/Git/version_control/reflections > git remote -v
origin	https://github.com/thebuunkenator/reflections.git (fetch)
origin	https://github.com/thebuunkenator/reflections.git (push)
erik@Firefly ~/Documents/Computer/Git/version_control/reflections > 

git push origin master # arg1: remote you want to push changes to, #arg2 local branch