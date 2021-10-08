# JenkinsContainer
Create container with Jenkins Web App for your DevOps environment 

## Download latest image o jenkins from docker hub to local registry
```bash
docker pull jenkins/jenkins:latest
```
## Verify downloaded image
```bash
docker image ls
```
## Execute this command for to create a container with installed jenkins web app
```bash
docker run -p 8080:8080 -p 50000:50000 --name jenkinsContainer -v volumeTest:/var/jenkins_home jenkins/jenkins
```
## Save the password for admin, example
074aa20ada7f493d88ee47766dc6b02e

![savepasswword_jenkins](https://user-images.githubusercontent.com/90909936/136528912-c28d6100-10f2-428d-aa20-170bc9d6a153.PNG)

## Open the web app Jenkins on localhost:8080 and configure it and Unlock Jenkins with the saved password
![unlock_jenkins](https://user-images.githubusercontent.com/90909936/136528951-69c435bc-ecf0-41a6-b71a-d282fbb569ad.PNG)

## Install Plugin and configure Jenkins for the first use
![image](https://user-images.githubusercontent.com/90909936/136529287-25fd4d1b-6184-437f-ba2d-ce9048fc351d.png)

