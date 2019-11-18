## COURSE PROJECT

# PART 1 : REFERENCE GUIDE

The following is a guide on a few basic commands useful in Windows Powershell, Docker, Bash, and Git.

# Powershell

1. Get-Process: Outputs a list of the processes running along with their process IDs. Generally used in conjunction with "stop-process".

   ![get-process](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/get-process.JPG)
   
2. New-Item -Path "Path" -ItemType "File/Folder": A command used for the creation of files and directories.

   ![new-item](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/newitem.JPG)

3. cd "Path": Used to change from the current directory to the specified path.

   ![change directory](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/cd_forw.JPG)
   
   The command "cd .." is used to go to the previous directory.
   
   ![change directory backwards](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/cd_back.JPG)
   
# Docker

1. docker commit "container_ID": Allows users to take a running container and save its current state as an image. The container ID is acquired by listing all the available containers.

   ![commit](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/docker_commit.JPG)

2. docker images: Lists all current images in the docker container.

   ![images](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/docker_images.JPG)

3. docker kill "container_ID": Kill one or more running containers.

   ![kill](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/docker_kill.JPG)

# Bash

1. ls: Lists all files and folders in the current working directory.
   
   ![list](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/ls.JPG)

2. touch "filename": Used to create files.
   
   ![touch](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/touch.JPG)

3. mkdir "directory_name": Used to create directories.

   ![mkdir](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/mkdir.JPG)

# Git

1. git checkout "branch_name": Used to change from one branch to the branch specified.

   ![checkout](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/git_checkout.JPG)

2. git commit -m "Custom_message": Used to clarify the commit to be made. Displays teh message to master for approval of the commit.

   ![commit message](https://github.com/mkm662169/mkm662169.github.io/blob/master/images/git_commit-m.JPG)
