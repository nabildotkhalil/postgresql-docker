# postgresql-docker

0. Build the image
```
sudo docker build -t nabil/database .
```

0. Run the container from the previously built image
```
sudo docker run --name=mydatabase -e POSTGRES_USER=docker -e POSTGRES_PASSWORD=docker -e POSTGRES_DB=docker -p 5432:5432 --net=mynetwork nabil/database
```
