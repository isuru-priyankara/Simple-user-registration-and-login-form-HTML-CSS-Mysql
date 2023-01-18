# Simple-user-registration-and-login-form-HTML-CSS-Mysql
Simple user registration and login form (HTML,CSS,Mysql)

![interface](https://user-images.githubusercontent.com/121779329/213194094-e4d34f15-5a2b-4eef-8633-284d7033824e.jpg)


Database Name--LoginSystem

Tabale Name--users


CREATE TABLE IF NOT EXISTS `users` (
 `id` int(11) NOT NULL AUTO_INCREMENT,
 `username` varchar(50) NOT NULL,
 `email` varchar(50) NOT NULL,
 `password` varchar(50) NOT NULL,
 `create_datetime` datetime NOT NULL,
 PRIMARY KEY (`id`)
);
