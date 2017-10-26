# docker-compose-lamp-app

Clone repository.  
Navigate into created folder.  
Optionally change environment variables in the `docker-compose.yml` file. 
Put your application into `app` directory.  
Optionally put your .sql, .sql.gz, .sh files like dumps, etc into `data` folder.  
Run `docker-compose up -d`.   
Navigate into <http://localhost/> on Linux and Mac or <http://docker-machine-ip/> on Windows.  
Observe "It works" page.  

Environment variables for database settings doesn't take effect after the first run.
