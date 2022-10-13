# Branching Cycle With Rebase

## Step 1

Before creating any new branch,

    ALWAYS pull to main!!!

    git checkout main
    git pull

## Step 2

Move to your feature branch and rebase with main

    git checkout <branchName>
    git rebase main

## Step 3

Branch of the feature branch to create a new branch to 
work on

    git checkout -b <branchName>

## Step 4

Make your changes, comitting each time you complete a whole
small task

    git add .
    git commit -m"<commitMessage>"


## Step 5

When you have completed your task, it's time to push you branch to GH

    git push origin <branchName>

## Step 6

Create a pull request and merge your branch with the relevant feature branch
Delete your branch

## Step 7 

Create a pull request and merge the relevant feature branch with the main branch.
DO NOT DELETE THE PERMANENT FEATUE BRANCH

## Step 8

Go back to your repo, checkout to main, delete your branch no longer in use, 
and repeat the process, starting with 

    git pull