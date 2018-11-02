
Once you created a database, user and password, adapt the database_* keys of your app/config/parameters.yml file. Here is an example for using Sulu with MySQL:



parameters:
    database_driver: pdo_mysql
    database_host: 127.0.0.1
    database_port: null
    database_name: hellosulu
    database_user: hellosulu
    database_password: averystrongpassword


When you’re done with the configuration, populate the database with Sulu’s default data:

bin/adminconsole sulu:build dev