# portfolio-website

## Prerequisites:
docker and docker-compose should be installed and up and running on your system
Git also install on your system

## How to run container on your system
apt update && apt upgrade -y
apt install git


git clone https://github.com/abdulsaad209/portfolio-website.git
cd portfolio-website.git
docker-compose up -d
docker container ls
curl http://localhost:80 
