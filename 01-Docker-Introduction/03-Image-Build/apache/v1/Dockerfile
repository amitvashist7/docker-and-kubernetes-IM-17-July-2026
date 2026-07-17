# Base Images 
FROM ubuntu:20.04 

# Update APT-Repo
RUN apt-get update 

# Update Env Variables 
ENV DEBIAN_FRONTEND=noninteractive
ENV TZ=Etc/UTC

RUN apt-get install -y tzdata apache2

CMD ["/usr/sbin/apache2ctl","-D","FOREGROUND"] 
