# DockerNetworking
Bridge network etc


$docker network ls

$docker pull alpine

$docker run -dit --name alpine1 alpine ash

$docker run -dit --name alpine2 alpine ash

$docker container ls

$docker network inspect bridge

$docker attach alpine1

  ping google.com and other container ip from this 

$docker container stop alpine1 alpine2



Remember, the default bridge network is not recommended for production. To learn about user-defined bridge networks, continue to the next tutorial.


