# Dockerproject

# Steps to create Docker Image:

Installed docker on AWS EC2 Instance 

Deployed python service and Html directly into docker in app.py

Created a DockerFile
Created a dockerimage named cclaxmi
Docker works without .sh file

# How to Run DockerImage:


• “docker load -i assignmentlaxmi.tgz” 
• "docker pull laxmipolam/cclaxmi"
• “docker run -d -p 8081:80 laxmipolam/cclaxmi”

# Functionality :

Select some date for which you want to forecast data for the next 5 days.

You will get a forecast graph of (minimum temperature and maximum temperature) based on average from previous years data.

Other graph will show minimum temperature and maximum temperature graph of coming 5 days (Irrespective of the selected date).

Application is made using Flask python , html and Bootstrap
