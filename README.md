How to use VS Code with Git and Github

Install VS Code
 1. Go to the website provided below and download the version for your operating system.
    - Link: https://code.visualstudio.com/ 
 2. Run the installer
 3. Open VS Code

Install Git
1. Follow the same steps as you did for VS Code
   - Link: https://git-scm.com/
2. Verify if you successfully installed Git
   - Open VS Code
   - Click on the Terminal > New Terminal > Git Bash
   - Type in: git --version
   - A version of Git should appear, if not you missed a step

Create GitHub Account
1. Search up https://github.com/
2. Sign Up

Configure Git in VS Code
1. Open up VS Code
2. Open the Git Bash Terminal, read instructions above if you forgot how
3. Type the following commands but replace the words inside the quotations with your information. This is just so that git can recognize who is pushing and pulling commits.
   - git config --global user.name "Your name"
   - git config --global user.email "Your email"

Create Repository
1. Go to https://github.com/
2. Click the "New" button
3. In the General Section simply choose an owner, add a project name, and write a description
4. For Configuration it all depends on your project
5. Once you finish click "Create repository"

Clone Repository
1. On the repository you just created click on "Code" and copy the HTTPS url
2. Open VS Code and click "Clone Repository"
3. It'll take you to the search bar, just paste in the url for your repository
4. Select a folder where you want the repository to be stored

Make Changes, Commit, and Push
1. Open up a file and make any changes
2. In the Git Bash Terminal type:
   - git add "file_name" // This line stages a file for the next commit
   - git commit -m "Specific and clear message of what changes you made" // This line saves a version of the changes you made to your local repository
   - git push origin "branch_name" or "main" // This line pushes the changes to your remote repository (GitHub)
