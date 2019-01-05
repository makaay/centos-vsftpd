# centos-vsftpd
vsftpd container on CentOS

This creates a centos container running vsftpd, disabling anonymous users and system users.

In order to build image:
docker build -t whatevernameyouwant -f centos-vsftpd . 

In order to run container:
docker run -d --name myftp nameyousavedimageto:latest
