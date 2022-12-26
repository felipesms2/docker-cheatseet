# docker-cheatseet
Common commands neededs

# Install

apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin


# Create Instance
  
  docker container run --name test_deb -it debian bash

# Run Instance

  docker container start -ai test_deb

# Stop All Containers

docker stop $(docker ps -q)

(<a target='_blank' href='https://www.unixtutorial.org/docker-stop-all-containers/'>from this website</a>)
