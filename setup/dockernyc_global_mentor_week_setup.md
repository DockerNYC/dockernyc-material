1. RSVP here: http://www.meetup.com/Docker-meetups/events/234781356/

1. Create a Docker Hub account here: You will need a Docker Hub account to access the course materials. 

1. Set-up Docker on your laptop (you will need to bring your own computer) 

Linux users: we need you to install Docker engine and Docker compose. Make sure you have Docker compose version 1.6 or higher by running docker-compose version from the command prompt. 

Mac users: install Docker for Mac or if you have an older Mac, Docker Toolbox. 

Windows users: if you have Windows 10 pro install Docker for Windows, otherwise install Docker Toolbox. If you want to try the new Windows containers, go through the setup steps in the Windows Container lab. It is essential to run this command in Powershell before coming to the event:

`docker pull microsoft/windowsservercore:latest`

New to Docker? pre-pull the docker images for the very basic tutorial so you’re ready for the beginner level course.

```
docker pull hello-world 
docker pull alpine 
docker pull seqvence/static-site
```

To run the application and participate in the rest of the training, pre-pull these images

```
docker pull microsoft/dotnet:1.0.0-preview1 
docker pull node:5.11.0-slim 
docker pull python:2.7-alpine 
docker pull redis:alpine
docker pull postgres:9.4
```

For the Ops / orchestration part, you will want to pre-build the demo app by running the following steps

```
git clone git://github.com/jpetazzo/orchestration-workshop
cd orchestration-workshop/dockercoins
docker-compose build
```

