# projectTest
A test repository for my first even github usage

--- TO BEGIN WITH ---
Go to github.com and create a new repository. Then copy the URL to the repository before proceeding with 'git clone ...'

If you get stuck in a commit (happens if you forgot -m), then do this: press ESC, then type in ':wq'

--- GO TO THE FOLDER YOU WANT THE REPOSITORY TO BE IN ---
In my case, it would be under Documents\Git.
Using git bash, navigate to folder using $ cd Documents/Git
This will clone the repository on github cloud locally to your PC at that location. 

Simply enter 'git' for help.

Clone to PC using Git Bash:
$ git clone https://github.com/USERNAME/REPOSITORY.git

Check difference between your repository and the repository on github cloud:
$ git status

Add new changes to the cloud: (suggested to use git status after this to check status. E.g. "Changes to be committed...") (use git add -A to add all in the repository)
$ git add file.type

Commit changes locally on your machine: (-m means add a message)
$ git commit -m "added file.type"

Push to github cloud to sync:
$ git push

Receive updated files from github cloud: (might need to do this first if git push gives error)
$ git pull


--- ON VISUAL STUDIO CODE ---
1) Go to source control.
2) Press checkmark to commit.
3) Press '...' to push.

3.1) Might need to '...' to add Remote and then paste repository link. 
