Docker Compose enviroment for dna2 developers
in a console:

``` 
$ ./stack start
``` 
or if you already cloned 

``` 
$ docker-compose up 
``` 

or as a deatached process

``` 
$ docker-compose up -d
``` 
If you have already a local webserver just change the port mapping for the web service in the docker-compose.yml file:

80:80
by 
freeport:80

then complete setup:

http://localhost/setup


and you have an c9 full ide integrated editor on
http://localhost:9022/
