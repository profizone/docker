## Docker Notes

List of Docker related resources such as: commands, links, images, Dockerfiles etc.

### Docker Commands

```Shell
# list all containers - including stopped ones
docker ps -a
```

```Shell
# list all docker images
docker images
```

```Shell
# start docker container with a given name
docker start kali-desktop

#stop docker container with a given name
docker stop kali-desktop
```

```Shell               
# remove docker image 
docker rmi my-kali

#remove docker container by name
docker rm my-kali

#remove docker container by id
docker rm  61206fe42352   
```

```Shell
# create container based on image: yoshiqui/kali-desktop and give container a name: kali-dekstop    
docker run -d -p 6080:6080 --name kali-desktop yoshiqui/kali-desktop:xfce
```



        
