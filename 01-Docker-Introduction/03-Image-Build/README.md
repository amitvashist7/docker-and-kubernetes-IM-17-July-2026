    1  mkdir 03-Image-Build
    2  ls
    3  cd 03-Image-Build/
    4  ls
    5  docker run -it --name build-cont ubuntu:20.04 
    6  ls
    7  docker ps 
    8  docker inspect build-cont 
    9  curl 172.17.0.2
   10  ls
   11  mkdir apache/v1 -p 
   12  ls
   13  cd apache/
   14  cd v1/
   15  ls
   16  vim Dockerfile 
   17  ls
   18  docker build -t myapache . 
   19  docker images 
   20  docker run -d myapache 
   21  docker ps 
   22  curl 172.17.0.3
   23  cat Dockerfile 
   24  ls
   25  cd ..
   26  ls
   27  cp -rf v1 v2 
   28  ls
   29  cd v2/
   30  ls
   31  mv Dockerfile mydockerfile 
   32  ls
   33  vim index.html 
   34  ls
   35  vim mydockerfile 
   36  ls
   37  docker build -t myapache:v2 . 
   38  docker build -t myapache:v2 -f mydockerfile . 
   39  docker images 
   40  docker run -d myapache:v2 
   41  curl 172.17.0.3
   42  curl 172.17.0.4
   43  ls
   44  cd ..
   45  ls
   46  docker ps 
   47  telnet 172.17.0.4 22
   48  telnet 172.17.0.4 80
   49  ls
   50  cp -rf v2 v3 
   51  ls
   52  cd v3/
   53  ls
   54  vi index.html 
   55  ls
   56  vim mydockerfile 
   57  ls
   58  docker build -t myapache:v3 -f mydockerfile . 
   59  docker images 
   60  docker run -d myapache:v3 
   61  docker ps 
   62  curl 172.17.0.4:80
   63  curl 172.17.0.5:80
   64  curl 172.17.0.5:3306
   65  curl 172.17.0.5:3305
   66  curl 172.17.0.5:22
   67  cat mydockerfile 
   68  cd ..
   69  l
   70  cd ..
   71  s
   72  ls
   73  cd 03-Image-Build/
   74  ls
   75  history 
   76  history > README.md 
