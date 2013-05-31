Testing Git
===========

Repository for testing Git commands


#Commands

##Create Git Projects

git init 			-> manage existing project with git

git clone [URL]		-> clone project to work with

##File States

tracked - already added with 'git add' command

	unmodified: nothing to do with these

	modified:	use 'git add' to mark changes for commitment (staged state)

	staged:		ready for being commited

	
untracked - use 'git add' to mark changes for commitment (staged state)


some commands

	'git status' 					- shows the states of the files

	'git add *'						- mark all modified and new files for commit (make them in staged state)

	'git diff' 						- shows what is changed but still unstaged

	'git diff --staged' 			- shows what is staged

	'git commit -m "first commit"' 	- do commit files in the git repository with comment

	'git commit -a'					- do commit even unstaged files

##Ignoring Files

Put patterns for file ignoring inside .gitignore

## Synchronize With Remote Location

if origine still does not exists do: 

	git remote add origin [location] e.g. location = https://github.com/pltod/dependency-management.git
	 
and push the files:

	git push origin master
