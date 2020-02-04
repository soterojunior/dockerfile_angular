# Docker image with Angular



## Description

- Docker with NPM, NGINX and ANGULAR. The versions can be customized from the Dockerfile.

## Setup Dockerfile

1. Build the image:

   `docker build -t #{_name_image_} .`

2. Run an instance of the image, mounting the directory:

   `docker run -p 80:80 #{_name_image_} `