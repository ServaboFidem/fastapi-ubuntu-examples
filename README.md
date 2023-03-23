# fastapi-ubuntu-examples
Example config for fastapi-ubuntu docker image with traefik frontend.

To use, simply start by building your dockerfile.  Copy your source code into the app directory.  Update requirements.txt.

then cd into the app directory, and run the following command:
docker build -t my/tag-name .

Update the docker-compose.yml's microservice section with whatever you set your tag to....
docker compose up -d

Done!