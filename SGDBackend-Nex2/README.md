### This is an attempt to use dockers

Steps on how to use the file.

1. The `DockerFile` is used to generate image.
2. This image can be used to quickly spin up the backend for sgd.

How to build image from DockerFile :computer:
```sh
$ docker build -t <image_name> .     #Do not miss the . at the end
```

To run the image you just build :rocket:
```sh
$ docker run --rm -it <image_name>
```
The published image on docker hub [sgd-backend](https://hub.docker.com/repository/docker/sagarjha/sgd_backend)
