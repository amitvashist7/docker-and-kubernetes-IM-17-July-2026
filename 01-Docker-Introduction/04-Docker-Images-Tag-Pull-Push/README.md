  ```
  113  docker images 
  114  docker login 
  115  docker push myapache
  116  docker tag be159b833814 amitvashist7/docker-and-kubernetes-im-17-july-2026-apache 
  117  docker images 
  118  docker push amitvashist7/docker-and-kubernetes-im-17-july-20
  119  docker push amitvashist7/docker-and-kubernetes-im-17-july-2026-apache
  120  docker tag c795e9aeaf9c amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  121  docker tag 15fee9d173dd amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3
  122  docker push amitvashist7/docker-and-kubernetes-im-17-july-2026-apache
  123  docker push amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2
  124  docker push amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3
  125  docker kill $(docker ps -q)
  126  docker rm $(docker ps -aq)
  127  docker ps -a 
  128  docker images 
  129  docker rmi $(docker images -q )
  130  docker rmi $(docker images -q ) --force 
  131  docker ps 
  132  docker images 
  133  docker run -d  amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3
  134  docker images 
  135  docker ps 
  136  curl 172.17.0.2
```
