# Get started with Docker Compose

[[source](https://docs.docker.com/compose/gettingstarted/)]

## Docker Machine on a Mac or Windows

Use docker-machine ip MACHINE_VM to get the IP address of your Docker host. Then, open http://MACHINE_VM_IP:5000 in a browser.

```
docker-machine ip MACHINE_VM
```

## Build and run application with Compose
```
docker-compose up -d
```

## Stop the application
```
docker-compose down
```

## Bring everything down, removing the containers entirely
```
docker-compose down --volumes
```