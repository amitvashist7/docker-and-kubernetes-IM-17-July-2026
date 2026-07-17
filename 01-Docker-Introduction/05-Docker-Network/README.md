```
  155  git add . ; git commit -m "Docker" ; git push 
  156  docker ps 
  157  docker kill $(docker ps -q ) 
  158  ip addr 
  159  route -n 
  160  ip route 
  161  docker network ls 
  162  docker network inspect 8da69005e36e
  163  ls
  164  docker run -id ubuntu 
  165  docker run -it ubuntu 
  166  l
  167  ls
  168  docker images 
  169  docker ps 
  170  docker commit -p 24408ca1a948 ubuntu-nettool:v1 
  171  ls
  172  docker ps 
  173  docker network ls 
  174  docker ps 
  175  docker run -itd --name host-cont --network host ubuntu-nettool:v1 
  176  docker run -itd --name none-cont --network none ubuntu-nettool:v1 
  177  docker ps 
  178  docker exec -it bridge-cont ifconfig 
  179  docker exec -it host-cont ifconfig 
  180  ls
  181  docker exec -it none-cont ifconfig 
  182  ls
  183  ip addr 
  184  docker images 
  185  docker run -itd --name none --network none amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 
  186  docker run -itd --name host --network host amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 
  187  docker run -itd --name bridge --network bridge amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 
  188  docker ps 
  189  docker inspect none
  190  docker inspect host
  191  ip addr 
  192  curl 172.31.0.100
  193  curl 172.31.0.100 -vvv 
  194  curl 172.31.0.100
  195  docker run -itd --name bridge --network bridge amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  196  docker run -itd --name bridge-2 --network bridge amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  197  docker ps 
  198  docker inspect bridge-2
  199  curl 172.17.0.5
  200  curl 172.31.0.100
  201  docker run -itd --name bridge-3 --network bridge -p 8081:80 amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  202  docker ps 
  203  curl 172.31.0.100
  204  curl 172.17.0.5
  205  curl 172.31.0.100:8081
  206  docker run -itd --name bridge-4 --network bridge -p 8081:80 amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  207  docker ps 
  208  docker run -itd --name bridge-5 --network bridge -P amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v2 
  209  docker ps 
  210  docker run -itd --name bridge-6 --network bridge -P amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 
  211  docker ps 
  212  docker images 
  213  docker ps 
  214  docker inspect amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3
  215  docker inspect amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 | grep -i 3306 
  216  docker inspect amitvashist7/docker-and-kubernetes-im-17-july-2026-apache:v3 | grep -A5 3306 
  217  docker ps 
  218  ls
  219  cd 01-Docker-Introduction/
  220  ls
  221  mkdir 05-Docker-Network 
  222  ls
  223  cd 05-Docker-Network/
```
