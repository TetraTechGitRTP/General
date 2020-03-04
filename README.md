# Set Up Tetra Tech GitHub Repository
1) Download Git at https://git-scm.com/download/win. Select 64 bit for Windows. 
2) Do not change any of the installation defaults and continue clicking next until Git is installed.
3) Create a folder where you'd like to store all Tetra Tech repository files. We suggest creating the folder C:\GitHub (path is used in the rest of these examples).
4) Create a GitHub account using your TetraTech email address at www.github.com.

# Creating new repository
1) Project manager should navigate to the Tetra
2) Open command line by clicking the start menu and typing "cmd" and hit ENTER.
3) Navigate to where you'd like to store all Tetra Tech repo files. We suggest C:\GitHub and use it in the rest of these examples.
4) In the command line type "git clone https://github.com/BRPickard/Temp_TetraTech_Tutorial.git" and hit ENTER.
5) Navigate to your GitHub folder and you should see your repository and all the files.

# Creating a new branch when modifying code ###
This general workflow is a simple approach for using GitHub for versioning control. All of this is done in the command line after navigating to the folder within your GitHub local folder. There are really only about 5 commands that you need to remember to use GitHub from the command line. After you have modified all of your code, follow these steps to push these changes to a branch.

1) Get the latest version of the files by typing git pull and hit ENTER.
2) Check to see which "branch" you are working in by entering git branch and hit ENTER.
3) Create a new branch by typing git branch newbranchname and hit ENTER. Note the "newbranchname" can be whatever you want it to be. This creates a copy of the master.
4) Switch to new branch by typing git checkout newbranchname and hit ENTER.
5) Add your new code to the branch by typing git add -A and hit ENTER.
6) Commit the changes and include a description by typing git commit -m "1-line descriptive text about your change" and hit ENTER.
7) Push the changes to GitHub repository by typing git push.
8) You will likely be given a prompt for pushing the current branch upstream - highlight the git push command git provides and copy/paste it into the command line, then hit ENTER.

# Modifying the master branch
If you want to commit the changes from a branch to the master branch follow these steps. 
1) Enter the branch with modified code by typing git branch newbranchname and hit ENTER.
2) Type git merge master to have git combine the master branch with the modified code. 
3) You will likely have merge conflicts that will need to be sorted out. You must fix the conflicts and then commit them by typing git commit -m "desription". When you get a long commit message and are stuck enter the ESC button and then type :wq and hit ENTER to finish the commit. 
4) This is to test the next steps go.
5) Second test for banching...
