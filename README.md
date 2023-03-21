docker-compose -f v1-docker-compose.yml up

docker container ls -a

docker-compose -f v1-docker-compose.yml down

docker container ls -a

#-----------------------------------------------------------------

docker volume create --name=mysql-volume

docker inspect mysql-volume

sudo snap install mysql-shell

mysqlsh

\connect root@localhost:3308

\sql

show databases;

create database marvel;

use marvel;

create table infinity_war (infinity_stones VARCHAR(30));

show tables;

insert into infinity_war values("time_stones");

select * from infinity_war;

down and up

show tables;



