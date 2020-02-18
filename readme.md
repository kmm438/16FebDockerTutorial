# Docker Tutorial
## Kimberly McDaniel


## Part 1: Orientation and Setup
1. Installed docker on my Mac and tested it with docker --version
2. Tested docker installation via docker run hello-world

![Docker part 1](part1-docker-helloworld.png)



## Part 2: Build and run your image
1. Cloned git repository into my repository 
2. Merged the two repositories 
3. Build my docker image with docker image build -t bulletinboard:1.0 .
4. Run my image as a container with docker container run --publish 8000:8080 --detach --name bb bulletinboard:1.0
5. Delete my container docker container rm --force bb
![Docker part 1](part2-runningimage.png)



 
