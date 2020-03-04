# Setting up Tetra Tech GitHub account and local repository
1) Download Git at https://git-scm.com/download/win. Select 64 bit for Windows. 
2) Do not change any of the installation defaults and continue clicking next until Git is installed.
3) Create a folder where you'd like to store all Tetra Tech repository files. We suggest creating the folder C:\GitHub (path is used in the rest of these examples).
4) Create a GitHub account using your TetraTech email address at www.github.com.

# Creating new repository
1) The Project manager should log into the main TT git account using the following information - Username: TetraTechGitRTP; Password: !!Tt123456
2) Once logged in, click on the repositories tab and click the green NEW button.
3) Follow on screen instructions to set up your repository to suit your specific needs.

# Adding repository to your local drive
2) Open command line by clicking the start menu and typing "cmd" and hit ENTER.
3) Navigate to where you'd like to store all Tetra Tech repo files locally, we suggest C:\GitHub and use it in the rest of these examples.
4) In the command line type "git clone https://github.com/TetraTechGitRTP/Name_of_repository.git" and hit ENTER.
5) Navigate to your GitHub folder, you should now see that specific repository and all relevant files.

# Creating a new branch when modifying code 
This general workflow is a simple approach for using GitHub for versioning control. All of this is done in the command line after navigating to the folder within your GitHub local folder. There are really only about 5 commands that you need to remember to use GitHub from the command line. After you have modified all of your code, follow these steps to push these changes to a branch.

Prior to starting code modifications:
1) Get the latest version of the files by typing git pull and hit ENTER.
2) Check to see which "branch" you are working in by entering git branch and hit ENTER.
3) Create a new branch by typing git branch newbranchname and hit ENTER. Note the "newbranchname" can be whatever you want it to be. This creates a copy of the master.
4) Modify your code. (This can be done over minutes or weeks).

When your ready to upload your new code to the branch:
1) Switch to new branch by typing git checkout newbranchname and hit ENTER.
2) Add your new code to the branch by typing git add -A and hit ENTER.
3) Commit the changes and include a description by typing git commit -m "1-line descriptive text about your change" and hit ENTER.
4) Push the changes to GitHub repository by typing git push.
5) You will likely be given a prompt for pushing the current branch upstream - highlight the push command git provides and copy/paste it into the command line, then hit ENTER.

# Modifying the master or sub-branch
If you want to commit the changes from a branch to the master branch (or sub-branch) follow these steps. 
1) Log into github.com with your username and password.  
2) Select the repository you are working on. 
3) Under the branch dropdown list select the branch where your modified code is.
4) Click the compare and pull request button. 
5) Enter a title and description for the specific changes to the code you made. 
6) Click the green SEND PULL REQUEST button.
7) Ideally, another member of the team should review the pull request before clicking on the MERGE PULL REQUEST button. However, for our teams most individuals will be merging pull requests themselves.
8) Once the merge pull request is complete you can delete the branch, should you so desire.

# Gmail login info:
Account - TetraTech.Git.RTP@gmail.com
Password - TT1234
