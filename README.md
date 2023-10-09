## Hagital Cloud Engineer Program: Git-Lesson-101  
## Download Git Bash from the website below  
- https://git-scm.com/download/  
## Configure Git Bash
- git config --global user.name "yinka"
- git config --global user.email "lawal.adeyinka@gmail.com"
## Prepare working environment  
- mkdir website "this command help to create a directory called website"  
- cd website "this command is used to enter into the directory called created"  
- git init "this command is used to initialize the directory"  
- touch index.html "this command helps to create an html file called index.html"  
- vim index.html "this command is used to edit the html file created, add a simple html code"  
- :wq "save and exit the file. Note: you will need to press 'esc' key before this command"
## Clone your Repo  
- git remote add origin (url) "this is the url from your project Repo, use https"  
## Push/Upload to GitHub Repo  
- git add index.html  
- git commit -m "add a message"
- git push origin master  
