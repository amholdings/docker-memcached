# docker-memcached
amholdings/docker-memcached

Docker Image for running Memcached on CentOS 7

# Build Container:
git clone https://github.com/amholdings/docker-memcached.git

cd docker-memcached

docker build --tag="docker-memcached" .

# Run Container as daemon:
docker run -d --name "docker-memcached" -p 11211:11211 -t amholdings/docker-memcached
