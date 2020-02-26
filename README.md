# Git & Github Workshop  

## Install Git  

Windows:  
> https://git-scm.com/  

Linux:  
> $ sudo apt install git  

Mac:  
> $ git  

## Create a Github Account  

> https://github.com  

## Student Upgrade  

> https://education.github.com/pack/offers  

## Basic Unix Commands  

### These work in the following command lines  

- Linux  
- Windows subsystem for linux (wsl)  
- Git Bash (From installing on windows)  
- Mac  

Make a new directory:  
> $ mkdir {directory name}  

List the files in the present working directory:  
> $ ls  

Change the directory:  
> $ cd {directory name}  

List the present working directory:  
> $ pwd  

Create a file:  
> $ touch {file name}  

## Git Commands  

Initialize the git repository:  
> $ git init  

Add a file to the staging area:  
> $ git add {file names}  

( . will add all files with a change)  
(seperate multiple files with spaces)  

Commit these files:  
> $ git commit -m "{your commit message}":  

Clone a repository to the present working directory:  
> $ git clone {repository link}  

Show the current status of the repository:  
> $ git status  

## Git Config  

git config --global user.name "YOUR GITHUB USERNAME"  
git config --global user.email "GITHUB EMAIL"  
git config --global credential.helper {$}  
> The "$" above can be one of store or cache.  
> By default it will not cache or store the password.  

## Extras  

For working in teams learn:  

- git checkout command  
- github branches  
