# Git-Learner-101
A collection of resources to learn git

### What we learnt in the git session - 
## Git install -
	 sudo apt-get install git

## Git config - 
	git config --global user.name "Your user name"
	git config --global user.email "Email"
	git config --global core.autocrlf input
	git config --global core.safecrlf true

## To check whether settings are correctly configured - 
	git config --list

## To change the config settings use this command (use your favourite editor like subl, nano, etc instead of gedit) -
	gedit ~/.gitconfig  				

## git staging and commiting
	git status
	git add <file>
	git commit -m "File message" 
	git commit 		(Opens vim editor to enter commit message)

## Seeing all your commit history (newest commits on top) 
	git log 

## Changing the default editor for entering commit messages 
	git config --global core.editor <editor_name> 		(subl, gedit)



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
