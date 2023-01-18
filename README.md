# Simple-user-registration-and-login-form-HTML-CSS-Mysql
Simple user registration and login form (HTML,CSS,Mysql)

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
