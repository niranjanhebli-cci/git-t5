
## Name: Yuron Livon D'Costa
## Tech : Git 
## What I understood so far: 
Git : The version control system itself, which you can use locally or with any remote repository.<br>

GitHub: A web-based platform for hosting and sharing Git repositories, providing additional features like pull requests, issue tracking, and project management.
<br>


    <<---Git Commands-->

    git clone  
    Clones a repository from a remote location

    git add .
    adds all files as it looks now to your next commit.

    git commit -m “added readme file” 
    commits the staged changes in the repository.

    git status
    shows which files are tracked, untracked, or staged for the next commit 

    git pull
    show all commits in the current branch’s history.

    git push 
    Transmit local branch commits to the remote repository branch

    git log
    show the commit history for the currently active branch

    git checkout
    used to switch between branches, restore working tree files, or check out specific commits in a Git repository, updating the working directory to match the version stored in the target branch or commit



 
## What I don’t understand so far: 
Need more practice on git merge ,git stash 

# **Name :** Niranjan Hebli

#  **Tech :** Git 

## **What I understood so far :**

**Repository (Repo):** A Git repository is a storage space where the project files and the entire history of their changes are kept. It can be local (on the computer) or remote (on a server). The repository tracks all changes made to the files, allowing us to revert to previous versions, collaborate with others, and manage our project’s development efficiently.

**Commit:** A commit is a snapshot of the repository at a specific point in time. Each commit has a unique ID and contains a message describing the changes made.

**Branch:** Branching allows us to create separate lines of development within a repository. Each branch can have its own commits and changes, enabling us to work independently from the main codebase. The main branch is typically the default, but we can create new branches using `git branch [branch-name]` and switch between them with `git checkout [branch-name]`. Once our work is complete, we can merge branches back into the main branch using `git merge [branch-name].` This helps in managing and organizing different development tasks efficiently.

**Merge:** Merging is the process of integrating changes from one branch into another. This is often done to incorporate new features or bug fixes into the main branch.

**Clone:** Cloning is the process of creating a copy of an existing repository. This is useful for getting a local copy of a remote repository to work on.

**Pull:** Pulling means fetching changes from a remote repository and merging them into your local repository. This keeps your local repository up-to-date with the remote one.

**Push:** Pushing means sending your local commits to a remote repository. This is how you share your changes with others.

To modify a Git repository, start by cloning it to our local machine using the `git clone` command followed by the repository URL. This creates a local copy where you can make changes. 
Navigate to the repository directory and create a new branch with `git checkout -b <branch-name>` to keep our changes isolated. Make modifications, whether it’s adding, editing, or deleting files. Use `git add .` to stage the changes and `git commit -m "commit message"` to commit them. This ensures our changes are tracked and documented.

Once changes are committed, we have to push them to the remote repository using `git push origin <branch-name>`. This uploads our branch and its changes to the remote server. If we are working in a collaborative environment, we can create a pull request on the repository’s hosting platform to merge our changes into the main branch. 
Reviewers can then review and approve your modifications. 

Finally, once approved, merge the pull request to incorporate the changes into the main codebase. This workflow helps maintain a clean and organized project history.


### **Benifits of GIT**


**Distributed System:** Every developer has a full copy of the repository, including its history, which allows for better collaboration and backup.

**Speed:** Git is designed to be fast, handling large projects efficiently.

**Branching and Merging:** Git’s branching model is flexible and allows for easy experimentation and collaboration.


**What I don’t understand so far:**
rebasing, stashing 


## Name: Shaun Steve Pereira
## Tech : Git 
## What I understood so far: 

- Git is version control system which helps developers to maintain changes in files and have mulitple version of a particular code, since there different verions of a particular file the developer can revert to the previous changes if he wants to. Git helps in collabrative work where multiple developers can work together and contribute to single file or repository.
- There are multiple commands in git few of the main ones which are often used are
    - `git init`: this is used to intialize git in a particular folder
    - `git commit`: this command is use to commit changes.
    - `git push`: this command is used to push the recent commited changes to the remote repository 
    - `git add`: adds files to the staging area.
    - `git pull`: its used to pull the recent changes done in the remote repository.
    - `git clone`: this command is used to clone or copy a remote repository to to your local repositories.
    - `git checkout`: this command is mostly used to switch between multiple branches in a repo.
    - `git branch branch_name`: this commmand is used to create a new branch.

## What I don’t understand so far: 

- How to resolve any confilts if there are any in a particular branch
- How to use the `merge, stash, revert,rebase` command 

## Name: A Aravind Sagar
## Tech : Git 
## What I understood so far: 

- Git is a vital version control system that tracks changes in files and manages different versions of a project, making it indispensable for software development. It supports collaborative work by allowing multiple developers to contribute to a project simultaneously while maintaining a detailed changelog of all modifications. I’ve familiarized myself with Git through Git Bash, a command-line interface (CLI) that offers powerful control over Git's functionalities.

- I learned basic Git commands such as `fetch`, `pull`, `status`, `add`, `commit`, `push`, and `init`, which are essential for managing and updating a repository. Additionally, I practiced more advanced commands like `clone`, `branch`, `checkout`, and `merge`, which are crucial for branching strategies and integrating changes.

## What I don’t understand so far: 

- Although I have used the `merge` command a few times, I feel that I need to use a few more times, perhaps in more complicated situations to be completly proficent in it.  

- I have not used the following commands and would like to learn about them:  
`revert`, `diff`, `stash`.

