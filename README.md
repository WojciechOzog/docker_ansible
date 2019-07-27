# docker_ansible

# build required images
docker build -f Dockerfile-ansible-image7 -t ansible-image7 .
docker build -f Dockerfile-host-centos -t host-centos .
docker build -f Dockerfile-host-ubuntu -t host-ubuntu .
