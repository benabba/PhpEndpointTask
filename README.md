Most parts of the projects are done excepte the Docker part, 
the files of it are ready but still i need to fix some configiration

**Genereal informationn about how to run the project: 

Download or clone the project from git.
Start mysql.
Start PHP Server.
Import the Database (db.sql) into MySql (for creating the database annd the table)
Open the project in a IDE.
//Excute those commande (composer install, composer dump-autoload)
Change the database configuration on Confg.php (user, password, MySql port, access key)
    *For the access key, Use a Free api key. 
Open terminal and run (php -S localhost:XXXX) in XXXX you can select any emty port you like ex:80000.
Open the link that you get in the terminal (http://localhost:XXXX).
To run the test excute vendor/bin/phpunit