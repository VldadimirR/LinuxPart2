1. 
```console
root@vladim-VB:~$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=test123 -v /test/mysqltest:/var/lib/mysql -d mysql:latest
```

2. 
```console
root@vladim-VB:~$ docker run -it -h vladim-VB --name gb-test ubuntu:22.10
```

3.

```console
mysql> CREATE TABLE books
(
id INT,
title VARCHAR(100),
author VARCHAR(50)
); 
```
```console
mysql> INSERT INTO books
(id,title,author)
VALUES
(1,'Dubrovsky','Pushkin');
```



```console
mysql> INSERT INTO books
(id,title,author)
VALUES
(2, 'War and Peace', 'Tolstoy');
```

```console
mysql> INSERT INTO books
(id,title,author)
VALUES
(3, 'Quiet Don', 'Sholokhov');
```