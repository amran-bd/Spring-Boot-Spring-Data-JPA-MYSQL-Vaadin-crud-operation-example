# Spring-Boot-Spring-Data-JPA-MYSQL-Vaadin-crud-operation-example
Focus on Vaadin UI Framework


Crud Operation Introduce and you can understand vaadin with Spring Boot Framework.

Database MYSQL:

Script:
create database testdb;

DROP TABLE IF EXISTS `testdb`.`user_todo_info`;
CREATE TABLE  `testdb`.`user_todo_info` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `item_name` varchar(100) NOT NULL,
  `description` varchar(500) NOT NULL,
  `created_date` date NOT NULL,
  PRIMARY KEY (`id`) USING BTREE
) ENGINE=InnoDB;

just run the project with database connectivity you can see todo application. You can do add, remove, update, list etc.
