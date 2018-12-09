# IODOCK

## How to user

- ```cd your/project_directory/path```
- ```git submodule add https://git.iotech.co.th/iotech/iodock.git```
- หรือ ```git clone https://git.iotech.co.th/iotech/iodock.git```
- cd iodock
- ```mv env-example .env```
- ```docker-compose up -d```

## Work with php

```bash
docker-compose exec [--user=1000] php-fpm sh
```

## WORKSPACE TREE

|---- project  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`|---- iodock <<< **clone iodock here**

## ROAD MAP

- workspace container
- nodejs
- python
- phpmyadmin