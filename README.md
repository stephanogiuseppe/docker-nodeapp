## MOUNT A DOCKER IMAGE
docker build -t stephanogiuseppe/docker-nodeapp .

## RUN IMAGE
docker run -p 3000:3000 -d stephanogiuseppe/docker-nodeapp

## UPDATE
docker-compose up
