# Simple Docker Container for Echo Server

## Description
testing docker image downnload using github

## installing
open your terminal window, enter the following commands
```
git clone https://github.com/Chrispullen2001/dockertest.git

```
You may have to install docker-compose
```
sudo apt install docker-compose -y
```

If everything is successful, you can run
```
cd Dockerfile
docker compose build
```

## Execute 
In order to run this code, open a terminal and run the following command
```
docker run -it bionic-bai:latest
echo -n password | iconv -t UTF-16LE | openssl md4
```
Open a second terminal and run
```
docker-compose --profile echoserver up
```
Opena a third terminal and run 
```
python3 echo-client.py abcd
```
