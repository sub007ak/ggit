Title : Git Tutorial
This is the readme file to show git commands.
- git init : to initialize current 
- git clone <url> : to bring the repo from <URL> to current folder
- git status : tell the status of current repo and its state
-This is just line
Another unsaed line
= git add <FILE> : add file to staging area
- git commit : open text editor  to write commit message.
- git commit -m <message> :  write one line message to commit history
- git log : shows the commit logs
- git log --oneline : log of one line
- git diff : compare current state with last committed state
- git diff --staged : compare staging file to commiteed files.
- git diff HEAD~1 : compare with head <NUM>
- git diff <HASH> : compare with commited hash
- git restore --source <hash> <file> : file to restore from history
- git checkout <hash> <file> : restore file
- git checkout <hash> : in detatched sate
	- git checkout main
	- git switch main : going back to main commit.

#STARTED working on REMOTE
- git remote add <name> <url> : adding a remote location
	git remote add origin https://github.com/usrname/repo.git
	<name> is by convention origin
- git remote -v : show all the remote repo setup for local repo.
- git push <where> <what> : where = url, what = branch
- git remote remove <name>


---------------- Changes on web -----
- git pull <whare> <what> : pull from there where and which branch

