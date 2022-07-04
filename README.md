## Overview
This repo contains Dockerfiles that I use to set up containers to build certain categories of projects.

You can build and run a particular container by executing the following commands (using the container to build an image based on The Yocto Project):
```
$> cp Dockerfile.yocto ~/dockerfiles/Docker
$> cd ~/dockerfiles/Docker
$> docker build -t yocto-builder .
$> docker run -v"native path to src":/home/dev/src:z -i -t yocto-builder
```
