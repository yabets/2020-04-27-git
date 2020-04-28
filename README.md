# 2020-04-27-git

- init: create a git repository in current directory
- status: tells you what is going on 
- add: put file to staging area 
- commit: commit files from staging area to working branch with message
	- `commit -m `: commit with the message without opening up text editor
- `log`: look at all the commit history you've been doing
	- `log --oneline`: simple oneline log view
- `diff`: look at differences between current state and previous commits
- `checkout`: moving our head
- `HEAD`: place we're looking at right now on our computer

- remote: a lace where the git repo is stored, e.g., GitHub
	- `git remote add origin <URl>` add a remote
- `git push origin master`: to push the master branch on our local to remote named origin

## Collaboration
- `git clone <URL>`: download the repository from the web to current direcotry on local
- `git branch <NAME>`: create a new branch
- `git checkout <NAME>` or `git switch <NAME>`: switch to branch
	- `git swithc -c <NAME>`: create and switch to new branch 
