# docker-cheatseet
Common commands neededs

# Install

apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin docker-compose -y


# Create Instance
  
  docker container run --name test_deb -it debian bash

# Run Instance

  docker container start -ai test_deb

# Stop All Containers

docker stop $(docker ps -q)

(<a target='_blank' href='https://www.unixtutorial.org/docker-stop-all-containers/'>Detail</a>)

# Multiple Command

<br>
  need to start daemon before
<br>

docker exec debian2 "uname";"uname";ip addr;"uname"

# Delete All Stopped

docker container prune -f

# Mapd Dir

docker container run --name test_deb -v /home/felipe/apache:/var/www/html  -it debian bash

# Daemon

docker start test_deb

# Remove All Images

docker system prune -a
<br>
<a href='https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes#removing-volumes'>Detail</a>


