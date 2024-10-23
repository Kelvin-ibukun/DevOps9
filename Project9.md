# Project 9 - DOCKER

Docker is a containerization platform that simplifies how applications are built, shared, and run across environments. It ocker allows you to package your app and its dependencies into a small, isolated unit known as a container.

## Dockerfile: Building First Image

### Spinning of Instance

Using the knowledge from previous projects, i spinned an Ubuntu server ans SSH into the instance

### Installing and Starting Docker

- I ran commands as shown below:

![1](img/1.png)

-To install Docker:

![2](img/2.png)

- To start and check the Status of Docker:

![3](img/3.png)

### Cloning the Docker Project Repository:

![4](img/4.png)

- The docker file

![5](img/5.png)

### Running the Docker Application

- To build the Docker Image:

![6](img/6.png)

- To check if the image built

![7](img/7.png)

- To check the Docker Container

![8](img/8.png)

![9](img/9.png)

- To test if the browser is running properly, go to browser and access the EC2 public IP as shown below:

![10](img/10.png)

- As seen above, the page will not load as we have not added the port 8000 to the inbound rules of our security group of our instance as shown below:

![11](img/11.png)

- Once that is done, reload the browser and we should have the image shown below:

![12](img/12.png)

## Pushing the image to docker hub

### Create a Docker Hub Account.

- After creating a Docker hun=b account, I followed the steps below:

![13](img/13.png)

![14](img/14.png)

### Log In to Docker Hub from Terminal with the steps shown below:

![15](img/15.png)

![16](img/16.png)

After pushing the image, I followed the steps as shown below:

![17](img/17.png)

![18](img/18.png)

# The End
