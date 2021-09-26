# Reuse-Near-You
Reskill Americans Phase 3 Group Project

****************

A guide on how to use the repo
Team Contact: @cbojo5

Before you push your code to the repository, please make sure you pull from the main repository (), so that the changes that have been made can be reflected on your local machine. To avoid merge conflicts, use the git command line
   
    git pull upstream main

## Developers guide

This process here should be able to guide you on how to contribute effectively to this project, follow the steps below.

## Main is the default branch

    * Fork the repository to generate a copy of your own.

    * Clone the repository.

        ```
            git clone (the repository link)
        ```
        
    * Make your main repo the remote upstream 
        ```
            git remote add upstream https://github.com/cbojo5/Reuse-Near-You.git
        ```
    * swich to your branch 

        ```
        git checkout -b (name-of-branch)
        ```
    * create your file name. Your file name should be what you are working on. For example, if I am working on the sign in page, my file name should appear this way:.

        ```
        signin.html
        sigin.css (This should be placed in the css folder which is inside the assets folder on the repo)
        ```

    After changes have been made do:
        ```
        git pull upstream main
        ```
    Consistently pull from the upstream to avoid not getting your pull request merged and to avoid conflicts.
    This way you can resolve conflicts from your local computer even before pushing always check what branch you are on when making changes
    
    * Make your changes, add them and make your commits

        ``` 
        git add .
        git commit -m "your message"
        ```
    Write good commit messages.

    * Push your codes to your forked repository, make sure you are pushing to your branch please
        
        ```
            git push origin (name-of-branch)
        ```
    Make your Pull request from that branch of your repo to the branch of this repo and wait for it to be merged.

Your PR shouldhave a screenshot of the output to enable faster code review. 

Your branch name should be the name of the page you are working on. For example, if I am working on the signin page, my branch should be called "signin" and so on for others
