# URL-Shortener
An URL Shortener made with PHP

Steps to make this work - 
1. Fork this repository into your xampp installation inside htdocs folder
2. Create a folder named shorty
3. Create a Database named shorty
4. Create a Table using this SQL Query - 
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
