# A02
# Tutorial on how to get started on Git, WebStorm and GitHub:

**Step 1 - Install WebStorm:**

1) Download WebStorm from JetBrains at: https://www.jetbrains.com/webstorm/
   - If student go to: (https://www.jetbrains.com/student/) 
   - Click Request now. you’ll need to sign in or create a JetBrains account using your school email address.
   - After being approved, download and install Webstorm by running the installer and following the setup prompts

**Step 2 - Install Git as a Local Program**
1) Download from : https://git-scm.com/downloads
2) Find the downloaded file and install it. Make sure to double click on the file.

**Step 3 - Create a Github Account**
1) Sing up for an account at: https://github.com/join
2) Enter your email, create username and password
3) Once verified, your account would have been activated

**Step 4 - Connect Github with WebStorm**

Part 1:
1) Display system preference in Webstorm by pressing (Ctrl + Alt +S)
2) Choose Version Control -> Git. from the left side.
3) Click Test to make sure that Webstorm is connected to Git.
   - The path in the location box
should be:
C:\Program Files\Git\bin\git.exe. Auto-detect may find the git.exe file at C:\Program Files\Git\cmd\git.exe.
4) If Git is installed correctly, you should get the message “Git Executed Successfully.”

Part 2: **(Add Github Password to Webstorm)**
1) Once again, In Webstorm press (Ctrl+Alt+S) 
2) Select Appearance and Behavior --> System Settings --> Passwords
3) Add a location for the password file
4) Click OK

**Step 5 - Create Repository in GitHub**
1) In the upper right corner, select the + sign and choose "Create new repository"
2) When choosing visibility, make the repository public and add the readme file
3) Click create repository

**Step 6 - Create a Repository from Webstorm**
1) Select VCS and import into Version Control
   
**Step 7 -  Import a repository from Github**
1) From Main page Select Checkout from version control --> Git 
2) Enter Github repository name
3) Enter local path name
4) Click Clone

**Step 8 - Making a WebStorm file and adding it to Git**
1) Choose File --> HTML --> HTML 5 or File --> Stylesheet
2) The Add to Git dialog opens
3) Click Add. This stores the repository to local file system

**Step 10 - Commit your changes**
1) Choose the README.md file and review changes
2) Write a commit message that describes your changes
3) Click commit
   
**Step 11 - Push Change to Remote Repository**
1) If Click “Ctrl --> Shift --> K” Or “VCS --> Git-->Push"

**Step 12 - Choose GitHub Page Location:**
Part 1:
1) Select "Master branch"
2) Note the published URL

Part 2: **Check your GitHub Pages**
1) Note the published URL 
2) Copy the Github.io URL into a browser
3) Post the URL into Moodle with your Github account URL

**Step 13 - Submit the repository Link:**
1) Copy the repository link and submit it

# **Glossary:**

**Branch** – A separate line of development in a repository. It lets you work on new features or fixes without affecting the main code.

**Clone** – A full copy of a Git repository (including history) downloaded from a remote (like GitHub) to your local computer.

**Commit** – A saved change in Git. Think of it like a snapshot of your code at a specific point in time, with a message describing the update.

**Fetch** – Downloads changes from a remote repository but does not automatically apply them to your local branch.

**Git** – A distributed version control system that tracks changes in code and allows collaboration.

**GitHub** – A web-based platform for hosting Git repositories, with collaboration tools like pull requests, issues, and project boards.

**Merge** – Combining changes from one branch into another, usually bringing feature branch work into the main branch.

**Merge Conflict** – When Git cannot automatically combine changes from different branches because they edit the same part of a file. Requires manual resolution.

**Push** – Uploading your local commits to a remote repository (like GitHub).

**Pull** – Fetching changes from a remote repository and merging them into your local branch.

**Remote** – A version of your repository stored online (e.g., on GitHub) that your local repository can sync with.

**Repository** – A project folder tracked by Git, containing files, branches, and the full version history.

# Reference List:
* Murachs HTMI and CSS book
* https://njit.instructure.com/courses/58104/files/8421440/download?download_frd=1
* https://www.jetbrains.com/help/webstorm/using-git-integration.html
* https://njit.instructure.com/courses/58104/files/8421447/download?download_frd=1
* https://guides.github.com/activities/hello-world/ 
* https://chatgpt.com/c/68d69bf8-a11c-8326-bc6b-0b022d9350b1
