## COURSE PROJECT

# PART 1 : REFERENCE GUIDE

The following is a guide on a few basic commands useful in Windows Powershell, Docker, Bash, and Git.

# Powershell

1. Get-Process: Outputs a list of the processes running along with their process IDs. Generally used in conjunction with "stop-process"

2. New-Item: A command used for the creation of files and directories. The syntax is as follows:
   
   New-Item "Path" -ItemType "File/Folder"

3. dir: Used to list the files and directories of the current working directory.

4. cd: Used to change teh current working directory. It is of the syntax:

   cd "Path"

# Docker

1. docker commit: Allows users to take a running container and save its current state as an image.

2. docker images: Lists all current images in the docker container.

3. docker kill: Kill one or more running containers

# Bash

1. ls: Lists all files and folders in the current working directory.

2. touch: Used to create files. Is of the syntax:

   touch "filename"

3. mkdir: Used to create directories. Is of the syntax:

   mkdir "directory_name"

# Git

1. git branch -b "branch_name": Used to create a branch "branch_name"

2, git checkout "branch_name": Used to change from one branch to the branch specified.

3. git commit -m "Custom_message": Used to clarify the commit to be made. Displays teh message to master for approval of the commit.
