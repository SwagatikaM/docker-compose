# docker-compose

Permission denied-

sudo chmod 666 /var/run/docker.sockdocker pull mediawiki:1.34docker run --name my-mediawiki -p8080:80 -d mediawiki:1.34
docker ps


USING Docker compose-

sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

docker-compose up

docker-compose up --scale mediawiki=2
