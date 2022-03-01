# Archiveteam's Warrior Docker Compose File
## Introduction
The internet is a volatile place where content is constantly getting removed or censored, server crash all the time and bills don't get paid on time. It's very important to archive as much content as possible. You can help by installing the Warrior. It's a tool from the Archiveteam that automatically gets work from a project that is being archived at the moment. In this repository you will find a Docker Compose file to get you started. 

## Installing The Warrior
Installing the warrior is very easy: just download the `docker-compose.yml` file and run `docker-compose up -d` to start it up. You can access the warrior's GUI in your browser via `http://<your-ip>:8001/`. 

## Docker Compose Features
This Docker Compose file includes Watchtower, which will automatically update the warrior if a new version comes out. When closing, the warrior is given a 5 minute timeout window to finish any tasks it is currently working on. The configuration is done through environment variables, so you don't have to set up the warrior after each update. 

## Read more
You can read everything about this file and why I made this on my blog [selfhostedheaven.com](https://selfhostedheaven.com/posts/20220228-help-out-archiving/).
