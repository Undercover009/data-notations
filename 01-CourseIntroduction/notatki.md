# Logowanie do kompa

> git config --global user.name "Anna May"

>git config --global user.email "maya@gmail.com"

### żeby sprawdzić: 

>git config --list

# Create a Git repository. 

To do this, execute the command:

>git init

# Creating a file

>echo "" > 1.abc

Check the status of your repository. Execute the following command:

> git status

Add files to track. Run the command below.

>git add .

Register changes in your repository

>git commit -m "I created three files"

Display the history of the registered changes in folder

>git log

return to some previous state of your folder

> git checkout _**commit id**_

To return to the last state of the folder, execute the command:

> git checkout master

To push the content of your local repository to GitHub, execute the commands below. 

>git remote add origin https://github.com/Undercover009/FirstProject.git

>git branch -M main

>git push -u origin main

To download some data from the remote repository to your local repository, use the command:

>git pull

# Branch ;-;

List available branches.
> git branch

**Create** a new branch named new1branch:

>git branch new1branch

**Switch** to the branch new1branch

>git checkout new1branch

In the branch new1branch, create files and **register changes** in the branch new1branch.

>git add .

>git commit -m "added files"

to list the files.

>ls

Execute the command to merge new1branch branch to the current branch (i.e. master, so first switch branch to master obv!):

git merge new1branch

to delete a branch
>git branch -d new1branch


