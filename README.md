# Docker-change-the-default-subnet
I ran into a problem with the docker subnet(IP address conflict), and in this repository I will show you how to change the default docker subnet

## create the default subnet config file
Put the file daemon.json in /etc/docker

## restart docker
 - sudo systemctl restart docker

When you restart Docker, it will use your custom default subnet to execute the app in the container.


<br><br>

#Author
<b>Xiao Li Savio Feng</b>
