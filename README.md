# PlpbasicGitassignment

step-by-step guide 
Task 1: Repository Setup
1. GitHub Repository Creation:
    - i Logged in to my GitHub account.
    - i Clicked the "+" icon in the upper-right corner and select "New repository".
    - Named the repository `PLPBasicGitAssignment`.
    - i  Checked the box to "Initialize this repository with a README".
    - then Clicked "Create repository".

Task 2: Local Setup

2. **Local Folder Setup:**
    -  i Created a new folder on my local machine named `PLPBasicGitAssignment`.
    - Openes a terminal.
    - Navigated to the newly created folder using the `cd` command:
      ```bash
      cd path/to/PLPBasicGitAssignment
      ```

3. **Git Initialization:**
    - Initialized a new Git repository in my local folder:
      ```bash
      git init
      ```

4. **Connecting to GitHub:**
    - Linked my local repository to the GitHub repository:
      ```bash
      git remote add origin <https://github.com/Masingita25/PlpbasicGitassignment.git>
      ```
     

### Task 3: Making Changes

5. **Create a File:**
    - Inside my local folder, i created a new text file named `hello.txt`.
    - Add a simple text message to the file:
      ```bash
      echo "Hello, Git!" > hello.txt
      ```

6. **Committing Changes:**
    - Stage the changes:
      ```bash
      git add hello.txt
      ```
    - Commit the changes:
      ```bash
      git commit -m "Add hello.txt with a greeting"
      ```

### Task 4: Pushing to GitHub

7. **Pushing to GitHub:**
    - i Pushed the committed changes to my GitHub repository:
      ```bash
      git push -u origin main
      ```

### Task 5: Verification

8. **Verify on GitHub:**
    - i visited GitHub repository in my web browser to  Confirm that the `hello.txt` file is present and that the commit message "Add hello.txt with a greeting" is visible.
