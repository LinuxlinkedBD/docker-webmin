# docker-webmin
dockerfile for webmin

## Building the image
```
git clone https://github.com/LinuxlinkedBD/docker-webmin.git
cd docker-webmin
docker build -t docker/webmin .
```

## Running the container
```
docker run -d -p 10001:10000 docker/webmin
```

Log into webmin and manage your server
```
http://server_ip:10001
(docker:docker)
```
To change login username and password; Change **ARG USER** and **ARG PW** on Dockerfile or set value for these varibale during docker run 
