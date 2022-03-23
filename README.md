# SCA-Cloud-School-Application
This assessment is in partial fulfillment of the requirements for the She Code Africa Cloud School V3 Application.

**Description**:This is a simple python application that displays a webpage.

## Technologies Used
1. Python: A high-level, general-purpose programming language.
2. Flask: A micro web framework written in Python. Flask is used for developing web applications using python, implemented on Werkzeug and Jinja2.
3. Docker: an application build and deployment tool. A set of platform as a service products that use OS-level virtualization to deliver software in packages called containers.

## First task 
1. Clone the newly created repo. '''git clone 
2. Create the app.py which contains the code for the webpage.
3. Create a Dockerfile which will be used to build the image for the webpage.
5. Ensure that docker desktop is up and running.
6. Build the image ```docker build -t scacloudschool``` .
7. Run the container and check if the container is running on localhost:5000.
8. Update the Dockerfile so the webpage displays 'Welcome to SCA Cloud School Application , this is my first assessment'


## Test Process
Link to Docker Repository https://hub.docker.com/repository/docker/culnellie/sca-cloud-school-application

Instructions

1. Clone the repository.

2. Cd into the repository and checkout to the start branch.
3. Run docker ```build --tag  sca-cloud-school-application``` to build the docker image locally.
4. To test the application, use the command ```docker run -d -p 80:5000 sca-cloud-school-application```.

Note that the container will run on ```http:localhost:5000```

## Building on the exisitng image

You can pull this image directly from Docker Hub using the command ```docker pull culnellie/sca-cloud-school-application:latest```
