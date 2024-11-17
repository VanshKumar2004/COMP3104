
# Run following command on terminal

docker build --tag=app1 .

docker image ls

docker run -p 4000:80 app1
docker run -d -p 4000:80 app1

docker container stop CONTAINER_ID
docker rm CONTAINER_ID

docker container ls