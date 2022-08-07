## docker-wordpress


**環境構築**
``` bash
$ cd docker-wordpress/
$ docker compose up -d
``` 
**環境から抜ける**
```bash
$ exit
$ docker-compose down --volumes
$ docker image rm imageid
```
**確認**
```bash
$ docker image ls
$ docker container ls
```
