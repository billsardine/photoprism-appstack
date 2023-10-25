# PhotoPrism App Stack

Photoprism app stack based on the PhotoPrisim compose file [Compose Example]([https://link-url-here.org](https://docs.photoprism.app/getting-started/docker-compose/)) and with https://hub.docker.com/r/linuxserver/mariadb

Pull repo

```git clone https://github.com/billsardine/photoprism-appstack.git```

Copy the .env.example file to .env

```cp .env.example .env```

Change the variables in the .env file to appropriate values

Start the container in the console to verify settings

```sudo sudo docker-compose up```

Kill the container and start it in the background

```sudo sudo docker-compose up -d```
