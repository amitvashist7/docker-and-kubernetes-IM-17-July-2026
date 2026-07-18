   31  docker volume ls 
   32  docker volume create myvol 
   33  docker volume ls 
   34  docker volume inspect myvol
   35  cat /var/lib/docker/volumes/myvol/_data/
   36  docker run -it -v myvol -v /root/docker-and-kubernetes-IM-17-July-2026:/test-1:ro -v /root/docker-and-kubernetes-IM-17-July-2026:/test-2 ubuntu 
   37  ls
   38  mkdir 06-Docker-Volume 
   39  ls
   40  cd 06-Docker-Volume/
   41  ls
   42  history 
   43  history >> README.md
