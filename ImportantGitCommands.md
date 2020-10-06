# Git commands everyone should know
Below are some of the basic commands every beginner should know to navigate the git hub repositories.  Below are excerpts from Github
## 1. Clone
      git clone <https://name-of-the-repository-link>
  Git clone is a command for downloading existing source code from a remote repository (like Github, for example). In other words, Git clone basically makes an identical copy of the latest version of a project in a repository and saves it to your computer.
  Click on the Code button and You would be given the Clone link for the repository which you can use to download locally.
  
## 2. Branch
      git branch <branch name>
  This would create a branch which allows for developers to work parallelly.  

## 3. Checkout
    git checkout  -b <name-of-your-branch>  (will create a branch and move you into it)

This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.


## 4. Status
    git status
This command will give a status of the client and information as to if it has to be updated
  1. Number of Commits
  1. Number of adds

## 5.Add
    git add filename

    git add -a   ( will add all files)
When we create, modify or delete a file, these changes will happen in our local and won't be included in the next commit (unless we change the configurations).

We need to use the git add command to include the changes of a file(s) into our next commit.

## 6. Commit 
    git commit -m "commit message"
Git commit is like setting a checkpoint in the development process which you can go back to later if needed.

## 7. Move to branch
    git checkout master

From branch move to the master after committing

## 8. Merge 

    git merge branchname

This is merge the branch changes to the master
    

sdjfh