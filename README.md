# Create-Docker-Container-Flask-Python
Create Docker Container Flask Python | How to Use Docker to Containerise Flask Application in Python

### DOCKER COMMANDS
#### 1. Create New Docker Image
docker build -t appname:tagname .

#### 2. Show Created Docker Images
docker images

#### 3. Run Docker Image
docker run --name conatinername -d -p 7778:7777 appname:tagname

#### 4. Show ALL Container
docker ps -a

Example :-
CONTAINER ID   IMAGE                          COMMAND                  CREATED        STATUS                     PORTS                    NAMES
55ff23d25c   flaskapp:latest               "/bin/sh -c 'python3…"   5 hours ago    Up 5 hours                 0.0.0.0:7779->7779/tcp   flaskapp

#### 5. File Run on Host Port
http://0.0.0.0:7779


![api_run_docker](https://user-images.githubusercontent.com/46967951/213913357-79622486-88be-4a33-be29-f6ef7701cba0.PNG)
