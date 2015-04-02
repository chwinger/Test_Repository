# Capstone Project

# Setting up origin
Go to https://github.com/kachlikmatt/Capstone
On the far right, click Fork and fork to personal GitHub account
Create a folder to hold the repository on your personal computer
Using git bash, cd into that directory and enter these commands:

$ git init
$ git remote add upstream git@github.com:kachlikmatt/Capstone.git
$ git remote add origin git@github.com:cddigi/Capstone.git  #Replace with own fork URL
$ git pull origin master
$ git pull upstream master
$ git remote set-url --push upstream no_push  #Disables ability to push master to upstream
