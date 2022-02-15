# Docker Commands

**Docker run -itd image-name**
- Will pull the image from docker hub(if image not locally available) and run the container in detach mode
- i -> interactive
- t -> terminal
- d -> detach mode
- p -> port

> example:
```python
docker pull jenkins/jenkins
docker run -p 8080:8080 --name=jenkins-master -d jenkins/jenkins
```

**docker ps**
- will list all the running container

**docker ps -a**
- will list all the running and exited container

**docker images**
- will list all the images

**docker search image-name**
- will list search result
