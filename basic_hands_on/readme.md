### Docker Client Help
docker help

### Docker Client Specific Command Help
docker version --help

### Version Information
docker version

### System Level Info of Docker
docker info

### Search an Image
docker search nginx

### Running a container
docker run -d --name basic_nginx nginx

### Get a list of docker conatiners
docker ps

### Get a list of docker images
docker images

### Getting into the Conatiner
docker exec -it 

### Basic Commands
date
whomai
ps -ef
vim

(Oops... it says "bash: vim: command not found")

## Getting out of the container
exit

### Run an enhanced nginx
docker run -d --name enhanced_nginx saiakhil2012/nginx:with_vim

### Getting into the Conatiner
docker exec -it 

### Basic Commands
date
whomai
ps -ef
vim

(This time vim works :) )
