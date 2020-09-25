# projectTest
A test repository for my first even github usage

--- TO BEGIN WITH ---<br />
Go to github.com and create a new repository. Then copy the URL to the repository before proceeding with 'git clone ...'

If you get stuck in a commit (happens if you forgot -m), then do this: press ESC, then type in ':wq'

--- GO TO THE FOLDER YOU WANT THE REPOSITORY TO BE IN ---<br />
In my case, it would be under Documents\Git.
Using git bash, navigate to folder using<br /> $ cd Documents/_github <br />
This will clone the repository on github cloud locally to your PC at that location. 

Simply enter 'git' for help.

Clone to PC using Git Bash:<br />
$ git clone https://github.com/USERNAME/REPOSITORY.git

Check difference between your repository and the repository on github cloud:<br />
$ git status

Add new changes to the cloud: (suggested to use git status after this to check status. E.g. "Changes to be committed...") (use git add -A to add all in the repository)<br />
$ git add file.type

Commit changes locally on your machine: (-m means add a message)<br />
$ git commit -m "added file.type"

Push to github cloud to sync:<br />
$ git push

Receive updated files from github cloud: (might need to do this first if git push gives error)<br />
$ git pull

--------------------------------------------------------------------

HOW TO USE GIT THROUGH VS CODE

--- STARTING NEW PROJECTS ---
1) Create a repository on GitHub.<br />
1.1) Alternatively, create a new repository locally on the computer at your location.
2) Select Source Control on VS Code.
3) Select Clone Repository. <br />
3.1) To upload repository to GitHub, select Publish to GitHub. <br />
4) Select where to save the repository locally. 

--- PUSHING CHANGES TO GITHUB ---
1) Select Source Control in VS Code.
2) Select the ✔ to commit any changes to your files. Remember to add a descriptive message.
3) Select '...' and choose to push. <br />
3.1) If it asks to add Remote, then copy the repository URL on GitHub and paste it. 
<br />

--- REMOVE FROM GIT THROUGH VS CODE ---
1) Close folder on VS Code.
2) Open folder location through Explorer on PC.
3) View hidden items, and delete .git folder.

--- CLONE REPOSITORY FROM GITHUB ---
1) With a fresh VS Code, select Source Control.
2) Select Clone Repository and add URL. 

--- UPLOAD LOCAL REPOSITORY TO GITHUB ---
1) Open desired folder on PC with VS Code.
2) Select Source Control.
3) Publish to GitHub. (Alternatively CTRL+SHIFT+P and search for Publish to GitHub)
