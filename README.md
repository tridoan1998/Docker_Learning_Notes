# Docker_Learning_Notes

What is Docker?
=> Container object used to run application in a seperate environment. Similar to VM but lightweight and take less time to deploy. Physical hardware => Operation system such as Linux or Ubuntu => Docker Daemon => Images(Build Time) and then Container (Run Time)




docker image pull ubuntu:latest 
docker images ls 
docker container run -it /bin/bash
docker container stop [name of the container]
docker container rm [anme of the container]

git clone https://github.com/nigelpoulton/psweb.git 
cd psweb
ls -l 
