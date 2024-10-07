# Git (1)
## Info
Summary about Git. 
> Note: Written based on Professor Jakeoung Koo’s Lecture 6

## What is Git?
It's essential to use a _**version control system**_ for software development and other documentation works. 
Reference: https://github.com/git

## How to install
check pre-installed version
```sh
git --version
```
Install
```sh
sudo apt install git-all
```
## How to setup
### Config
There are three levels. 
| Level | Description |
| ------ | ------ |
| System level | Affrects all uses and repositories on the system |
| Global level | Affrects all repositories of a current user |
| Local level | Specific to the current repository |

```sh
git config --list
```
```sh
git config --global user.name "username"
git config --global user.email "email@gmail.com"
git config --global init.defaultBranch main
```
### Init
Initializing a Repository in an Existing Directory
```sh
git init
```

## Basic Command
### Status
Checking Repository Status
```sh
git status
```
### Add 
Adding a new file to be staged (tracked)
```sh
git add [file_name]
```
Adding all files to be staged (tracked)
```sh
git add .
```
### Remove cache
Unstaging a file
```sh
git rm --cached [file_name]
```
### Commit
Commit
```sh
git commit -m "commit message"
```
Show logs
```sh
git log
```
### branch
Change branch name
```sh
git branch
git branch -m master main
git status
```
