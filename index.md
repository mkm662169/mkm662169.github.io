## COURSE PROJECT

# PART 1 : REFERENCE GUIDE

The following is a guide on a few basic commands useful in Windows Powershell, Docker, Bash, and Git.

# Powershell

1. Get-Process: Outputs a list of the processes running along with their process IDs. Generally used in conjunction with "stop-process"

2. New-Item -Path "Path" -ItemType "File/Folder": A command used for the creation of files and directories.

3. dir: Used to list the files and directories of the current working directory.

4. cd "Path": Used to change from the current directory to the specified path.

   Image
   
   The command "cd .." is used to go to the previous directory.
   
   Image
   
   
# Docker

1. docker commit "container_ID": Allows users to take a running container and save its current state as an image. The container ID is acquired by listing all the available containers.

2. docker images: Lists all current images in the docker container.

3. docker kill "container_ID": Kill one or more running containers.

# Bash

1. ls: Lists all files and folders in the current working directory.

2. touch "filename": Used to create files.

3. mkdir "directory_name": Used to create directories.

# Git

1. git branch -b "branch_name": Used to create a branch "branch_name"

2. git checkout "branch_name": Used to change from one branch to the branch specified.

3. git commit -m "Custom_message": Used to clarify the commit to be made. Displays teh message to master for approval of the commit.
