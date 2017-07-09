# Ionic-3-Angular-4-PHP-Rest-API-User-Auth-Login-and-Signup

![nn](https://user-images.githubusercontent.com/12325386/27992888-f8c34364-64d0-11e7-8a06-410f7eb3e2d1.JPG)

# step

<li>Need to use php rest api    </li>
<li>download the php file in api folder</li>
<li> create new database name banana in phpmyadmin </li>


CREATE TABLE users(
user_id int AUTO_INCREMENT PRIMARY KEY,
username varchar(50),
password varchar(300), 
name varchar(200), 
email varchar(300)); 
 
CREATE TABLE feed(
feed_id int PRIMARY KEY AUTO_INCREMENT, 
feed text,
user_id_fk int
);
```

