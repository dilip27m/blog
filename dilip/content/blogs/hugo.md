---
title: "HUGO PROFILE"
date: 2024-03-31T22:53:58+05:30
draft: false
github_link: "https://github.com/dilip27m"
author: "dilip"
tags:
  - Hugo
  - Github pages
image: /images/post.png
description: ""
toc: 
---
# hugo

## Step-1
Install hugo in local server
sudo apt hugo
After installation to check whether installed or not type hugo server
choosen a theme from hugo themes. 
Read all the instructions given in the document .

Created a hugo site in local server,
# command
hugo new site dilip (dilip is hugo repository)

'cd' to dilip then 'cd' to themes

cloned the git repository of the hugo theme (hugo profile) 

## Step-2
Finally, the theme is in my local server.But, content of the owner .Now i need to change 
it ,to do this i have to replace the cofig.yoml of root with config.yoml in examplesite.

Now we can change all the stuff like name,socila media links and the data
but we are unable get blog and images on server for this we need to replace the content and static folders 
in the root with contents and static of example site and in themes folder copy the required files and folders to static 

Now we are accessble to bolgs and gallery 

# github pages
## Step-3
Created a repository in github with the name portfoilio and cloned it into local server
All the above steps are done in this repository it self 
thses are commands to upload our work in github
git add . (adds all the files)
git commit -m "add the message"
git status
git push origin main
now it is uploaded into git cloud server 
Go to github portfolio repository and go to settings 
open pages
change option to main instead of none and save it 
refresh it wait for 5 mins we will get a link of website 
