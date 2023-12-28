CREATE DATABASE uae CHARACTER SET utf8 COLLATE utf8_general_ci;
CREATE USER 'uae'@'localhost' IDENTIFIED BY 'uae';
GRANT ALL PRIVILEGES ON uae.* TO 'uae'@'localhost' WITH GRANT OPTION;
CREATE USER 'uae'@'%' IDENTIFIED BY 'uae';
GRANT ALL PRIVILEGES ON uae.* TO 'uae'@'%' WITH GRANT OPTION;
flush privileges;
