# Git & Github Workshop  

## Install Git  

Windows:  
> https://git-scm.com/  

Linux:  
> sudo apt install git  

Mac:  
> git  

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

mkdir <directory name>:  
> make a new directory  

ls:  
> list the files in the present working directory   

cd <directory name>:  
> change the directory  

pwd:  
> list the present working directory  

touch <file name>:  
> Create a file  

## Git Commands  

git init:  
> Initialize the git repository  

git add <list of file names (. will add all files)>:  
> Add a file to the staging area  

git commit -m "<your commit message>":  
> Commit these files  

git clone <repository link>:  
> Clone a repository to the present working directory  

git status:  
> show the current status of the repository  


## Git Config  

git config --global user.name "YOUR GITHUB USERNAME"  
git config --global user.email "GITHUB EMAIL"  
git config --global credential.helper cache  
> The above can be one of store, none or cache.  
