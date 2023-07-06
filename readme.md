This repository is about GIT commands

#git clone 

Creates a copy of an existing Git repository. 
Cloning is the most common way for developers to obtain a working copy of a central repository.

#git add 

Moves changes from the working directory to the staging area. 
This gives the opportunity to prepare a snapshot before committing it to the official history.

#git commit

Takes the staged snapshot and commits it to the project history.
Combined with git add, this defines the basic workflow for all Git users.

#git push

Pushing is the opposite of fetching (with a few caveats). 
It lets move a local branch to another repository, which serves as a convenient way to publish contributions. 
This is like subversion commit, but it sends a series of commits instead of a single changeset.

#git checkout 

In addition to checking out old commits and old file revisions, git checkout is also the means to navigate existing branches. 
Combined with the basic Git commands, it’s a way to work on a particular line of development

#git branch

This command is your general-purpose branch administration tool. 
It lets to create isolated development environments within a single repository.

#git fetch

Fetching downloads a branch from another repository, along with all of its associated commits and files.
It doesn't try to integrate anything into your local repository. 
This gives a chance to inspect changes before merging them with project.

#git pull

Pulling is the automated version of git fetch. 
It downloads a branch from a remote repository, then immediately merges it into the current branch. 
This is the Git equivalent of subversion update.

#git status

Displays the state of the working directory and the staged snapshot.
If user wants to run this in conjunction with git add and git commit to see exactly what’s being included in the next snapshot.

#git merge 

A powerful way to integrate changes from divergent branches.
After forking the project history with git branch, git merge lets put it back together again.

