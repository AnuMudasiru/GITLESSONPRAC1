# GITLESSONPRAC1
This lesson describes how to push code from your local computer to github which is a remote repository emphasizing the distributed nature of Git. 
## Download Git bash  
- https://git-scm.com/downloads  
## Configure Git bash  
- git config --global user.name "name"  
- git config --global user.email "email"
## Configure Local Environment  
- mkdir resume
- cd resume
- touch index.html
- git init
## Clone your repository  
- git remote add origin url (this should be the url from your created repo- use https)
## Push to Git
- git status
- git add Index.html
- git commit -m "Create name.html"
- git push origin master
## Convert File to Github Pages  
- Navigate to the settings tab of your repo
- From the general session locate Pages
- From the deployment and build session > Select the Branch document > click save
- Wait for one or more mins, refresh the page to retreive the github page for the file
  
