## kafka-connect-sample

### run image

* docker-compose up -d
* docker-compose ps

### mysql

* docker exec -it kafka-connect-sample-mysql-1 bash
* mysql -u root -p
* password: root
* show databases;
* use products;
* create table products(id int, name varchar(255));
* show tables;
* insert into products values(1,'mac book air');
* insert into products values(2,'iphone 14');

### control center

* http://localhost:9021

### kibana

* http://localhost:5601