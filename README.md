docker build -t yocto-builder .

docker run -v<native path to bsp>:/home/dev/bsp:z -i -t
