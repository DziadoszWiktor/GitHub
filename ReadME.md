# **GitHub**
## **1.** What Git is?
Git is defined as a Version Control System
## **2.** What Version Control?
Is the way where Programmers track their code changes, documents and other collections of information
## **3.** What is a Git Repository?
Is the "folder" where our projects are contained
## **4.** Git Repo cloning

    git clone https://github.com/username/repo
## **5.** Tracking changes

    git status
## **6.** Adding files
"-A" parameter stands for All, we can specify single files "example.txt"

    git add -A
## **7.** Commiting changes
"-am" stands for all and comment, in the brackets we can add a comment

    git commit -am "comment"
## **8.** SSH keys
Generating a local key (default file: user/.ssh/id_rsa)

    ssh-keygen -t rsa -b 4096 -C "email@example.com"
We generate 2 keys, private one and public one, the public is needed by github repo settings
## **5.** Publishing the Repo changes on GitHub

    git push (origin master)
## **5.** Starting a repo locally

    git init
    *adding file, commiting, but we cannto push*
    *creating a repo on GitHub*
    git remote add origin *link for repo*
    git remote -v (shows any remote repos)
    git push (-u for setting default origin master)(origin master)
## **5.** Git branching
Master is our default branch
![screen1](./screens/screen1.JPG)
Check branches

    git branch
Creating new branch

    git checkout -b *branchname*


## **5.** What Git is?

## **5.** What Git is?

## **5.** What Git is?


