# docker-desktop-opevas

Docker container 

installing Docker on Ubunto
sudo apt update
sudo apt install docker.io

install docker compose
**intalled by default on Docker Desktop 
sudo apt update
sudo apt install docker-compose-plugin
test docker compose version 

or you can you a link to help install with you 
MacOS.   https://docs.docker.com/desktop/mac/install/
WIndows  https://docs.docker.com/desktop/windows/install/

if you are going to use the openvas i suggest you use the docker desktop since it has already built in features that you dont have to already install 
making it eaier to use.

go into the terminla and begin your process on installing the desktop container 

To install OpenVas, run the command docker run -d -p 443:443 --name openvas mikesplain/openvas 
in your desktop terminal which will pull the image container from GitHub for installation. 
Once it reads back the installation was successful, you then need to set up your docker-compose file through the following:

you will go to a web browser and input https://localhost/ it will take you to restrickted click advance and then i should connect you
once you are here it will take you to greenbone sceurutiy assisant 
go to username its going to be admin then the password is admin as well. 

after this you will run task for it to run and inspect 

this makes the Docker Desktop the eaisest way to install and use containers 
hope this helps you out. Any questions please reach out to me 
