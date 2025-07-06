## Installation
* Mac Installation Instructions - https://docs.docker.com/desktop/setup/install/mac-install/

## Basic Commands
* go to 'docker hub'
* search for particular docker image for eg - 'geeting-started'
* pull the docker image (docker hub will show the command)
* run the docker image (docker hub will show the command)
* docker ps  ->  for running images
* docker images  -> for all images
* to stop a particular image : run (docker ps) comand in terminal -> Copy Container ID -> run (docker stop 'Container_ID') in terminal

## how to create a docker Image:

-> go to folder in which your files are
-> make a new file named 'Dockerfile'
-> refer the following link for what to write in Dockerfile : https://chatgpt.com/share/686a8137-e430-8008-9798-395149a3cc73
-> in terminal write: docker build -t 'img_name' . 
* . in the above line represents curren directory
-> docker run 'nameOfImage'     => in terminal to run

## how to push a docker image in docker hub
* terminal cmds:

docker login
docker tag local-image username/repo-name:tag
docker push username/repo-name:tag

## 


