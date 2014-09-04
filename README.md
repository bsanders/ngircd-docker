A Dockerfile to create an IRC server in a container.
=====================================================================

When run, this docker container will automatically start a basic IRC server on port 6667.

#### Usage: ####
sudo docker build -t ngircd
docker run -name ngircd_container -p 6667:6667 -t ngircd

#### Requirements: ####
Requires Docker.
