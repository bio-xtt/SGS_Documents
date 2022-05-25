# Installation and deploy
SGS is build with docker technology, which consists of SGS client and server. SGS browser client supports MacOS, Linux and windows systems. SGS browser server can only be deployed on Liunx or MacOS systems.

## Requirements
+ Liunx, Windows or MacOS systems
+ Docker 

## Installation on linux or MacOS
```shell
# download packages
wget "https://xxxxx/xxx.tar.gz"
gunzip xxx.tar.gz
./flutter_smart_genome
```

## Deploy new SGS server
SGS browser is mainly composed of two parts:SGS server and SGS client. After downloading and installing the SGS client, we also need to deploy SGS server for data visuliation. Here，we have developed a one-click deployment function that simplifies the installation steps, allowing users to quickly deploy their own native SGS services.

Note that only Linux or MacOS supports this function.


### First step:clicking the one-click deploy button
We need to open the SGS browser client and click the one-click deploy button, then we can choose this computer or remote computer to install SGS service:
![one-click](/pictures/3_1.png)



### Second step:Filling relevant information.
We need to provide server ip address, port, username, password information for SGS server installation. Then, entering the deployment interface and filling the root password again. 


#### Deploy on this computer
Deploy on this computer only need to offer root password.
![one-click](/pictures/3_2.png)

#### Deploy on remote computer
+ IP: the server IP address, we can view it by "ifconfig -a" command.
+ username: the name of user
+ password: the password of the server
![one-click](/pictures/3_3.png)


### Finish SGS deploy
After installation, we can see the web server, R server and local server.
![one-click](/pictures/3_4.png)
