# CMPG323-Overview-31370004


# cmpg 323 project 1
Project 1 - CMPG 323 Overview 31370004 - URL -https://github.com/Kingmeka33/CMPG323-Overview-31370004

Project 2 (API Development), a repository named CMPG 323 Project 2 will be created

Project 3 (Standards & Patterns), a repository named (CMPG 323 Project 3) will be created

Project 4 (Testing & RPA), a repository named (CMPG 323 Project 4) will be created

Project 5 (Reporting & Monitoring), a repository named (CMPG 323 Project 5) will be created

![Screenshot 2024-07-28 102225](https://github.com/user-attachments/assets/d91f4be2-41a4-4ab1-833c-f441514f1a95)

# branching strategies
I will make use of GitFlow strategy for each project because it offers a detailed structure with a few clearly defined branches. 
This strategy will allow me to use each type of branch for parallel processing and provide quality assurance for all the projects.

1,There will be a main or master branch that will be used as the backup or stable version.

2,There will be a develop branch where new features will be created.

3,Features will be created on their own separete branch and will be merged with the develop branch once implemented.

4,Bug fixes/hot fixes will also be created on their own branch and will be merged with the develop branch.

5,After each successfull feature or fix is added to the develop branch and the current version of the develop branch is stable, it will be merged with the main branch to be kept as the latest backup.

![Screenshot 2024-07-28 104420](https://github.com/user-attachments/assets/bf14cbd1-37e1-4b28-a614-9d3d714898f8)

# The use of .gitignore files:

.gitignore will be used in each project to list files that should be ignored when commiting changes, these files will include files that contain sensitive information or credentials, system files, log files and files that I want git to ignore.
below is a list of each project and wether or not the project will use .gitignore

Project 1 - .gitignore wont be used

Project 2 - .gitignore will be used to ignore credentials

Project 3 - .gitignore will be used to ignore credentials

Project 4 - .gitignore will include .local,.settings,.tmh,.objects folders

Project 5 - .gitignore will include node_modules, .tmp and, dist folders

# Storage of credentials and sensitive information:
I will be using git-secret to store credentials and sensitive information. git-sercret is a bash tool that is used to encrypt files in a repository. git-secret uses gpg to encrypt and decrypt files, a public key is used to encrypt files and a personal private key that is given to authorised users is used to decrypt files. The tell command is used to give users their own key and to give them access to the secret files. I will be implementing git-secret on a project's repo to save passwords, API keys and other sensitive information. These files will be encrypted and will not be accessible to anyone, except for people I give access to.

#Burndown Chart
This Burndown chart is created in excel and will be continuously updated throuhout the semester.
![Screenshot 2024-07-29 111030](https://github.com/user-attachments/assets/daf6e6d9-a771-446b-a2ee-8c39c931be9b)

