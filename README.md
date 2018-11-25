# docker-php7.2-fpm
Dockerized PHP7.2-FPM with Extra modules  
Original: _[docker/php7.2-fpm/Dockerfile](https://github.com/docker-library/php/blob/b99209cc078ebb7bf4614e870c2d69e0b3bed399/7.2/stretch/fpm/Dockerfile)_  
In-docker php7.2-fpm Usage: _[Dockerise your PHP application with Nginx and PHP7-FPM](http://geekyplatypus.com/dockerise-your-php-application-with-nginx-and-php7-fpm/)_  

## 추가된 Extensions/Libraries
- php7.2-gd (with PHP `--with-gd`)
- php7.2-pdo_mysql (with PHP `--with-pdo-mysql`)
- php7.2-zip (with PHP `--enable-zip`)
- php7.2-opcache (with PHP `--enable-opcache`)
- _[ZendOpcache](https://pecl.php.net/package/ZendOpcache)_
- OpenSSL library (deb package `openssl`)
- _[php-redis 4.2.0](https://pecl.php.net/package/redis)_ (custom-built)
- _[php-apcu 5.1.14](https://pecl.php.net/package/APCu)_ (custom-built)

## Dockerfile
- [바로가기](https://github.com/jungin500/docker-php7.2-fpm/blob/master/Dockerfile)
