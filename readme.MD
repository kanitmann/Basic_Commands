## Basic Commands ##
<br/>

Basic Commands for Bash, Linux, CMD, and GIT

1. [Bash](#for-bash)
2. [CMD](#for-CMD)
3. [Linux](#for-Linux)
4. [GIT](#GIT-Commands)
<br/>

- ### For Bash 
  - List command:
  ```bash 
   ls
    ```
  - Change Directory: 
  ```bash 
  cd 'directory_name'
  ```
  - Clear Page: 
  ```bash 
  clear
  ```

  - Make Directory:  
  ```bash 
  mkdir 'directory_name'
  ```
  - Remove Directory: 
  ```bash
  rmdir 'directory_name'
  ```


  - Edit a File:
  ```bash 
  nano 'filename'.extension
  ```
  - Create a File:
  ```bash
  touch 'filename'.extension
  ```
  - Remove a File:
  ```bash 
  rm 'filename'.extension
  ```
 <br/>
------------------------------------------------------------------
<br/>

- ### For CMD:

  - Change Directory:
  ```bash
  cd "filename".extension
  ```
  - List All Directories:
  ```bash
  dir
  ```
  Make Directory (folder):
  ```bash
  mkdir 'directory_name'
  ```
  - Remove Directory:
  ```bash
  rmdir 'filename'
  ```
   - Delete file:
    ```bash
    del 'filename'.extension
    ```
    - Shows manual help:
    ```bash
    help
    ```
     <br/>
------------------------------------------------------------------
<br/>

- ### For Linux:

  - Change directory:
  ```bash
    cd 'directory_name'
   ```
  - List all directory:
  ```bash
  ls
  ```
  - Make Directory:
  ```bash
  mkdir 'directory_name'
  ```
   - Delete file/dir (-f)   [here, (-f) means force]:
   ```bash
   rm
   ```
   - Displays the current Directory:
   ```bash
  pwd
   ```
  - Shows Manual Help:
  ```bash
  man
  ```
  <br/>
------------------------------------------------------------------
<br/>

- ### GIT commands:

  - clone a Repository:
   ```bash
  git clone <URL>
  ``` 
  - Initialising a GIT Repository:
   ```bash
    git init
    ``` 

  - Getting stagging status:
  ```bash
  git status
  ```
  - Show git log:
  ```bash
  git log
  ```
    - Add Files to Staging Area:
   ```bash
   git add .
   ``` 
  - Commit changes:
   ```bash
   git commit -m " "
   ```
   - Change Working Branch:
   ```bash
   git checkout 'branch_name'
   ```
    - Push Command:
   ```bash
    git push <remote name> <branch name>
    ```
    - Creating new Branch:
    ```bash
    git switch -c <new-branch-name>
    ``` 
    or 
    ```bash 
    git branch <new-branch-name>
    ```
    - Pull latest commit from remote:
   ```bash	
    git pull <remote> <branch>
    ```
    - View all branches:
    ```bash
    git branch
    ```
    - Delete Branch:
    ```bash
    git branch -d <branch-name>
    ```
    - Merge Repository: 
    ```bash
    git merge <repo name>
    ```
    - Compare Difference Between 2 commits
   ```bash
    git diff <commit_1 id> <commit_2 id> 
    ```
    


    ------------------------------------------------------------------
    For any issues or suggestions, please [Contact Me](mailto:mannkanit@gmail.com)