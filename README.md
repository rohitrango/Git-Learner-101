## Git install -
	`sudo apt-get install git`

## Git config - 
	```
	git config --global user.name "Your user name"
	git config --global user.email "Email"
	git config --global core.autocrlf input
	git config --global core.safecrlf true
	```

## To check whether settings are correctly configured - 
	`git config --list`

## To change the config settings use this command (use your favourite editor like subl, nano, etc instead of gedit) -
	`gedit ~/.gitconfig` 				

## Git staging and commiting
	```
	git status
	git add <file>
	git commit -m "File message" 
	git commit 	```	(Opens vim editor to enter commit message)


## Seeing all your commit history (newest commits on top) 
	`git log` 

## Changing the default editor for entering commit messages 
	`git config --global core.editor <editor_name> `		(subl, gedit)

## Adding a remote 
	```
	git remote add origin <remote_url>
	git remote -v 	```	(See all the remotes that are connected)

## Cloning a different repository
	`git clone <remote_url>`

### **Note**: If you have your own repository, then use `git init` to initialize it, `git add remote` to connect it to the remote server(github, gitlab, etc) and then `git push` and `git pull` to make changes. If you need to take code/files from a different repository, use `git clone <url>`.

## Push and pull (push updates files from local machine to remote, pull updates files from remote to local repository). Think it as 'pulling' or 'pushing' from remote to your local machine.

	```
	git pull <remote_name> <branch_name>
	git push <remote_name> <branch_name>
	```
## Git stash (to discard all the un-committed changes made after YOUR final commit, if you end up in a messy state or some state similar to that or when you want to pull from a remote repository)
	`git stash`

## Git diff (see the differences between latest commit and uncommitted changes)
	`git diff`

## Aliases (to reduce writing)
	alias gs = 'git status'

## Useful links
### [A free online course on learning git](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
### [Learn git in 15 minutes](https://try.github.io/levels/1/challenges/1)
### [Git game v1 - Basic](https://github.com/git-game/git-game)
### [Git game v2 - Advanced ](https://github.com/git-game/git-game-v2)
### [Learn git branching](https://pcottle.github.io/learnGitBranching/)

## For all the git senti junta, who are interested in learning more about how git works
### [Introductory talk on Git at LinuxConf](https://www.youtube.com/watch?v=3m7BgIvC-uQ )
### [Explore .git folder](https://www.youtube.com/watch?v=dBSHLb1B8sw)
### [Linus Torvalds on Git at Google](https://www.youtube.com/watch?v=4XpnKHJAok8)

##### Happy 'git'ting !!
