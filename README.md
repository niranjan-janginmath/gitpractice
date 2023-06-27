# gitpractice
Learn and Do practice


Problem Statement
Three Developers are working in Aperture Technology co. Their company wants a better Source 
Code Management System because the earlier tool had the tendency to save redundant code. 
Multiple Developers working simultaneously on the same block of code also caused problems. 
You are Mike, and your manager has given you the task of moving the company’s code base to 
git and Github. 

Action Items
• Create a local git repository and move the entire code base to it
• Create a new branch for a new feature you want to add to the application
• Merge back the created branch with the master branch
• Create a remote repository 
• Push the local repository to company’s remote repository

STEP 1 Create a local git repository and move the entire code base to it
# cd Downloads/			to move to Downloads folder 

# unzip sample-project.zip 		to unzip sample project zip file in gitbash

# cd sample-project 	to change folder from Downloads to sample-project 

# ls -l			to list files and sub directories 

# git init 		to create a local repo in sample project folder 

# git status 		to check the WD files which are tracked & untracked 
We can see files css/ fonts/ img/ index.html are untracked, files are in red color 

# git add . 		to stage all multiple files in folders (.) dot represents current directory 
We can see all the files are staged, the color of the files got changed to green, yet to commit all these files 

# git commit –m “committed all the files” 
We will make some changes to an existing file which is already committed then we can use –a flag with the commit command. -a is append these changes. 


If you got error like *** Please tell me who you are. Need to add user name and email id 
# git config --global user.name "Niranjan" 

# git config --global user.email janginmath@gmail.com 



STEP 2 Create a new branch for a new feature you want to add to the application
# git branch 		to check on which branch you are present 

# touch file1 		to create a file 

# git add file1 		 

# git commit –m “added file1” file1



STEP 3 Merge back the created branch with the master branch 

First switch to the branch you want merge into that is master.  

# git checkout master 

# git merge newfeature master 

# ls 



STEP 4 Create a remote repository 


STEP 5 Push the local repository to company’s remote repository









