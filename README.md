
Assignment 1:

Demonstrate minimum 15 basic docker command with explanation and screenshot.

1. docker –version

This command is used to get the currently installed version of docker
![](image1.jpg)

2. docker pull

Usage: docker pull <image name>

This command is used to pull images from the docker repository(hub.docker.com)
![](image2.jpg)

3. docker run

Usage: docker run -it -d <image name>

This command is used to create a container from an image
![](image3.jpg)

4. docker ps

This command is used to list the running containers
![](image4.jpg)

5. docker ps -a

This command is used to show all the running and exited containers
![](image5.jpg)

6. docker image ls

Usage: docker image ls

This command is used to list all images that are locally stored with the docker engine
![](image6.jpg)

7. docker stop

Usage: docker stop <container id>

This command stops a running container
![](image7.jpg)

8. docker kill

Usage: docker kill <container id>
![](image8.jpg)

9. docker commit

Usage: docker commit <conatainer id> <username/imagename>

This command creates a new image of an edited container on the local system
![](image9.jpg)

10. docker login

This command is used to login to the docker hub repository
![](image10.jpg)

11. docker network ls

Usage: docker network ls

This command is used to list the networks
![](image11.jpg)

12. docker images

This command lists all the locally stored docker images
![](image12.jpg)

13. docker rm

Usage: docker rm <container id>

This command is used to delete a stopped container
![](image13.jpg)

14. docker rmi

Usage: docker rmi <image-id>

This command is used to delete an image from local storage
![](image14.jpg)

15. docker tag

Usage:  docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]

This command is used to retag a local image with new image name and tag
![](image15.jpg)
