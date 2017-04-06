Docker image based on Alpine, with addition of nodejs/npm, python3, golang 1.8,
and Hugo static site generator. This image has everything you need to build
a static blog using Hugo and deploy the results with Firebase Hosting
(I use it to build my blog [mcohen.io](https://www.mcohen.io)).

The makefile supports three tasks:

* make build - build the Docker image
* make push - publish the Docker image
* make sh - run an interactive Bash in the published Docker image

If you don't want to clone this repo and build your own image, you can also use my generated image directly 
from Docker Hub via ```docker pull marcacohen/hugo-image```.
