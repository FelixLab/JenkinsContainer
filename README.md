# JenkinsContainer
Create container with Jenkins Web App for your DevOps environment 

## Download latest image o jenkins from docker hub to local registry

docker pull jenkins/jenkins:latest

## Verify downloaded image

docker image ls

## Execute this command for to create a container with installed jenkins web app

docker run -p 8080:8080 -p 50000:50000 --name jenkinsContainer -v volumeTest:/var/jenkins_home jenkins/jenkins

## Save the password for admin, example

074aa20ada7f493d88ee47766dc6b02e

## Open the web app Jenkins on localhost:8080 and configure it
