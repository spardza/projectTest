# projectTest
A test repository for my first even github usage

--- GO TO THE FOLDER YOU WANT THE REPOSITORY TO BE IN ---
In my case, it would be under Documents\Git.
Using git bash, navigate to folder using $ cd Documents/Git
This will clone the repository on github cloud locally to your PC at that location. 

Clone to PC using Git Bash:
$ git clone https://github.com/USERNAME/REPOSITORY.git

Check difference between your repository and the repository on github cloud:
$ git status

Add new changes to the cloud: (suggested to use git status after this to check status. E.g. "Changes to be committed..."
$ git add file.type

Commit changes locally on your machine: -m means add a message
$ git commit -m "added file.type"

Push to github cloud to sync:
$ git push
