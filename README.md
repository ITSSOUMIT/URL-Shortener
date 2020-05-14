# URL-Shortener
An URL Shortener made with PHP

Steps to make this work - 
1. Go to xampp installation >> htdocs folder
2. Create a folder named shorty
3. Fork this repository inside shorty folder
4. Create a Database named shorty
5. Create a Table using this SQL Query - 
```mysql
CREATE TABLE IF NOT EXISTS `url_shorten` (
 `id` int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
 `url` tinytext NOT NULL,
 `short_code` varchar(50) NOT NULL,
 `hits` int(11) NOT NULL,
 `added_date` timestamp NULL DEFAULT CURRENT_TIMESTAMP
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```

Visit localhost/shorty to find your url shortener


Screenshots - 
1. ![Screen 1](https://github.com/ITSSOUMIT/URL-Shortener/blob/master/Screenshot%20(236).png "Screen 1")
2. ![Screen 2](https://github.com/ITSSOUMIT/URL-Shortener/blob/master/Screenshot%20(237).png "Screen 2")
