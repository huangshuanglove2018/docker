jdk base
A Dockerfile that installs the  openjdk1.8.0_121, centos.


# Prerequisite
Get and install Docker!

You should be able to run the docker command line without sudo. Otherwise you will have to make some adjustments.
# Usage
Bulid a new image:

$ git clone https://github.com/huangshuanglove2018/docker.git 

$ cd centos-openjdk1.8 

$ sudo docker build -t centos-openjdk1.8 . 

# OR
$ sudo docker build -t centos-openjdk1.8 https://github.com/huangshuanglove2018/docker.git
