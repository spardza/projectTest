# projectTest
A test repository for my first even github usage

--- TO BEGIN WITH ---<br />
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

--- CLONE REPOSITORY FROM GITHUB ---
1) With a fresh VS Code, select Source Control.
2) Select Clone Repository and add URL. 

--- UPLOAD LOCAL FOLDER TO GITHUB ---
1) Open desired folder on PC with VS Code.
2) Select Source Control.
3) Publish to GitHub. (ALternatively CTRL+SHIFT+P and search for Publish to GitHub)

--- REMOVE FROM GIT THROUGH VS CODE ---
1) Close folder on VS Code.
2) Open folder location through Explorer on PC.
3) View hidden items, and delete .git folder.

--- SUMMARIZED, REALLY ---
1) Create repository on GitHub, and copy the repository URL.
2) Open Git Bash, and enter $ git clone [URL].
3) Open folder on VS Code.
4) Do something like create a file or work on project.
5) Check Source Control (Alt+9).
6) Commit and add a message.
7) Press '...' and Push. 
