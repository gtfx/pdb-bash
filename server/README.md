# MOCK Server
Provides a mock api to test instead of "real" puppetdb server. Required Docker to run

## Running
To test with this server you need to have docker installed. First build the container
```
docker-compose up -d 
```

If you want to rebuild your container. Run the following command to rebuild without cache
```
docker-compose build --no-cache
```
