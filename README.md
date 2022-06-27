# CarpentryCon@Home 2020 Git Collaboration 
- 2022-06-27-maintainer-onboard
Maintainer Onboarding video - https://www.youtube.com/watch?v=uvWhSYBkZJ0
Carpentries Maintainer from CC@Home 2020
- 'git clone <url>': download the repo from the web to your computer
- make sure you are not in another repo
- just like 'git init' do only one per repo

- 'git log --oneline --graph --decorate --all' : shows you the git tree 

## Branches
- a branch is a label for a series of commits
- 'git branch <branch_name>': creates a new branch where you are 
- 'git switch <branch_name>': moves to the branch
	- 'git checkout <branch_name>' : the older way 

- 'git push <WHERE> <WHAT>'
- 'git push origin my_first_branch'

- shortcuts for creating branches:
	- 'git checkout -b <branch_name>'
	- 'git switch -c <branch_name>'

-'git branch -d <branch_name>': this will delete <branch_name> on your local computer. This only deletes on the local computer. It is easier to delete on github using a button. 
-'git fetch --prune': will update will update your local git tree with the remote
	- the prune will also delete references to branches that were deleted on the commit

-'git stash': saves your work temporarily 
	-'git stash list': to show your stashes
	-'git stash apply': to apply your last stash

## Tips and Tricks
- 'explorer . ' : will open the file explorer for the folder you are in
- 'nano FILENAME' : e.g. nano README.md will open the nano text editor 
- To save a file in nano - ctrl O
- To exit nano - ctrl X
- 'cat FILENAME' : prints the contents of a file
- To exit diff in shell 'q'


