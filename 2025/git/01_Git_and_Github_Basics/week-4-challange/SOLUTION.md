# Week 4: Git and GitHub Challenge

Welcome to the Week 4 Challenge! In this task you will practice the essential Git and GitHub commands and concepts taught by Shubham Bhaiya. This includes:

- **Git Basics:** `git init`, `git add`, `git commit`
    - `git init` : Used to initialise git into current working directory.
    - `git add` : Used to add unstaged file from local working directory.
    - `git commit` : Used to add meaning full message for previous staged file.
- **Repository Management:** `git clone`, forking a repository, and understanding how a GitHub repo is made
    - `git clone` : Used to make a clone of remote repository into local work directory.
    - `fork` : In github page we have an option to fork the repository directory to the remote repository.
- **Branching:** Creating branches (`git branch`), switching between branches (`git switch` / `git checkout`), and viewing commit history (`git log`)
    - `Creating branch` : To create a branch we can use `git branch branch_name` it will create an branch named `branch_name`
    #![Branch_log](./img/log.png)
    - `git checkout branch_name` : To switch to an existing branch.
    - `git switch branch_name` : To switch to an existing branch.
    - `git checkout -b branch_name` : To create a new branch `branch_name` and checkout to `branch_name`.
    - `git log` : Used to check the logs of all commits.
    #![logs]{./img/log1.png}
- **Authentication:** Pushing and pulling using a Personal Access Token (PAT)
    - 

- **Critical Thinking:** Explaining why branching strategies are important in collaborative development
    - Branching strategies that software development teams adopt when writing, merging and deploying code when using a version control system. 
        - A branching strategy aims to:
            1. Enhance productivity by ensuring proper coordination among developers
            2. Enable parallel development
            3. Help organize a series of planned, structured releases
            4. Map a clear path when making changes to software through to production
            5. Maintain a bug-free code where developers can quickly fix issues and get these changes back to production without disrupting the development workflow
        - `GitFlow` GitFlow enables parallel development where developers can work separately from the master branch on features where a feature branch is created from the master branch.
            - This branching strategy consists of the following branches:
                1. Master 
                2. Develop
                3. Feature- to develop new features that branches off the develop branch 
                4. Release- help prepare a new production release; usually branched from the develop branch and must be merged back to both develop and master
                5. Hotfix- also helps prepare for a release but unlike release branches, hotfix branches arise from a bug that has been discovered and must be resolved; it enables developers to keep working on their own changes on the develop branch while the bug is being fixed.

## Challenge Task
### Task 1: Fork and Clone the Repository
1. Fork the Repository:
    - 
2. Clone Your Fork Locally:
    -

### Task 2: Initialize a Local Repository and Create a File
1. Set Up Your Challenge Directory:
    - Inside the cloned repository, create a new directory for this challenge
    #![]{}

2. Initialize a Git Repository, Create a File, Stage and Commit Your File
    #![]{}

### Task 3: Configure Remote URL with PAT and Push/Pull
1. Configure Remote URL with Your PAT:

2. Push Your Commit to Remote:

3. (Optional) Pull Remote Changes:

### Task 4: Explore Your Commit History
1. View the Git Log


### Task 5: Advanced Branching and Switching
1. Create a New Branch:
    - Create a branch called feature-update `git branch feature-update`
2. Switch to the New Branch:
    - Switch using git switch `git switch feature-update`
3. Modify the File and Commit Changes:
    #![]{}
    