# Api login and register

## **Requirement**

1. PHP >= 7.1
2. OpenSSL PHP Extension
3. PDO PHP Extension
4. Mbstring PHP Extension

## **Problem**
> php artisan migratePHP Warning:  require_once(/home/arya/Documents/API/Login-Register-Api/bootstrap/../vendor/autoload.php): failed to open stream: No such file or directory in /home/arya/Documents/API/Login-Register-Api/bootstrap/app.php on line 3
PHP Fatal error:  require_once(): Failed opening required '/home/arya/Documents/API/Login-Register-Api/bootstrap/../vendor/autoload.php' (include_path='.:/usr/share/php') in /home/arya/Documents/API/Login-Register-Api/bootstrap/app.php on line 3

-solution : composer update

#Technology
 - Laravel Lumen
> Check the link and Documentation https://lumen.laravel.com/
> Version 5.6

 - Mysql
 - Apache Web Server
 - Xampp 7.1

## Import the Database
> php artisan migrate

## Making the Migration
> php artisan make:migration create_users_table --create=users

# Result by postman

### Register

![Test Register](https://cdn1.imggmi.com/uploads/2018/5/23/7555cc1697491ea95714dd10f1d99545-full.png)

### Login true
![Test Berhasil](https://cdn1.imggmi.com/uploads/2018/5/23/24f40db988b8f0e1772446f9f90c4bbe-full.png)

### Login false
![Test Gagal](https://cdn1.imggmi.com/uploads/2018/5/23/bcd0a5993108132a6604d435f124b210-full.png)


