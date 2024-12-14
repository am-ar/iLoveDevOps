## Steps to upload a new project to new github repository

# Summary:
Step 1: Create a GitHub Repository
Step 2: Initialize Git in the Local Project Folder
Step 3: Add the Files to the Repository
Step 4: Commit the Changes
Step 5: Link the Local Repository to the GitHub Repository
Step 6: Push the Changes to GitHub
Step 7: Verify the Upload

# Detailed Steps:
# Step 1: Create a GitHub Repository
1(a) Log in to GitHub
1(b) Create a new repository - 
    On the GitHub homepage, click on the "+" icon in the top-right corner, then select "New repository".
    Give your repository a name and choose visibility (public or private).
    For getting started, it's usually best to leave the option to add a readme uninitialized (i.e. leave the checkbox Add a README file, unchecked ).
    Click "Create repository".

and then 

git init
git add --all
git commit -m "Some meaningful commit message"
#git branch
#git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main

# Step 2: Initialize Git in our Local Project Folder
2(a) Open a terminal** (Command Prompt, PowerShell, or Terminal on macOS/Linux) and navigate to the project folder
    cd path/to/your/project

2(b)  Initialize Git
git init

# Step 3: Add our Files to the Repository
git add --all

# Step 4: Commit the Changes
git commit -m "Some meaningful commit message"

# Step 5: Link the Local Repository to the GitHub Repository
Copy the GitHub repository URL from our repository page on GitHub  (e.g., `https://github.com/username/repository-name.git`).

git remote add origin https://github.com/username/repository-name.git

# Step 6: Push the Changes to GitHub
git push -u origin main

If we want to push to a branch other than main, then we need to use that branch name instead of main

 # Step 7: Verify the Upload
 Go to our repository on GitHub in a web browser and verify that the recently pushed files have been uploaded.

