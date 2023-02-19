# docker-webapp
A Docker Web Application that Demonstrates the Use of a Dockerfile

## Usage
+ Firstly, download the source code to your machine using git command: `git clone https://github.com/BlueJayADAL/docker-webapp.git`
+ Secondly, build a docker image using the given files. 
`cd docker-webapp`
`docker build -t YOUR_DOCKER_HUB_NAME/catnip .`
where *YOUR_DOCKER_HUB_NAME* should be replaced by your user name on docker hub.
+ Thirdly, run the web app with command:
`docker run -p 8888:5000 YOUR_DOCKER_HUB_NAME/catnip`
+ Lastly, open up a web browser and type "localhost:8888" to the address bar.

Reference: https://github.com/prakhar1989/docker-curriculum
