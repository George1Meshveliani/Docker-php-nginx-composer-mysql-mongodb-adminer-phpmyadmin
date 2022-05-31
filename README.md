# PHP+COMPOSER+NGINX+MYSQL/MONGODB+ADMINER/PHPMYADMIN

## Simple docker project for beginners

This simple repository can help you install all necessary stacks to build simple PHP projects.

#### Instructions

1. `cd docker`
2. Start the project: `docker-compose up`
3. Website path: [localhost:8000](http://localhost:8000/)
4. Database path: [localhost:8080](http://localhost:8080/)
5. Database username: `root`
6. Initial password of the database: `changeme`
7. Shut down the project: `docker-compose down`

You can change your database password `changme` into `docker-compose.yml` file.

#### Stacks table

| Stack  | Description |
| ------------- | ------------- |
| PHP  | PHP (recursive acronym for PHP: Hypertext Preprocessor) - programming language, widely-used open source general-purpose scripting language that is especially suited for web development and can be embedded into HTML.  |
| Composer  | Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.  |
| MySQL  | Database management system  |
| MongoDB  | Database management system  |
| adminer  | Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.|
| phpmyadmin  | phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web. phpMyAdmin supports a wide range of operations on MySQL, MariaDB and MongoDB. Frequently used operations (managing databases, tables, columns, relations, indexes, users, permissions, etc) can be performed via the user interface, while you still have the ability to directly execute any SQL statement.  |



If you use old versions of OS, change version '3.8' with version '3.3' or '2.2' inside of docker-compose.yml file
