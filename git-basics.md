# Git Basics Cheat Sheet

## Setup
git config --global user.name "Your Name"
git config --global user.email "you@email.com"

## Starting Out
git clone <url>           # download a repo
git init                  # start a new local repo

## Everyday Commands
git status                # see what's changed
git add <file>            # stage a file
git add .                 # stage all changes
git commit -m "msg"       # save a snapshot
git push origin <branch>  # send to GitHub
git pull                  # get latest from GitHub

## Branching
git checkout -b <name>    # create + switch to branch
git checkout main         # switch back to main
git branch                # list all branches

## History
git log                   # see all commits
git diff                  # see unstaged changes
