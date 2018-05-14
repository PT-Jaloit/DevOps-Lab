#Wordpress example
Source: https://docs.docker.com/compose/install/ https://docs.docker.com/compose/wordpress/
mkdir my_wordpress
cd my_wordpress/
sudo nano docker-compose.yml

sudo apt-get install docker curl
sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose

docker-compose up -d