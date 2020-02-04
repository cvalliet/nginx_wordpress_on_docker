# nginx_wordpress_on_docker
Wordpress on docker (using nginx, php and mariadb)

## Installation

You must create the next directories :

    mkdir -p db-data
    mkdir -p logs/nginx
    mkdir -p wordpress
    
## Container management

Start container :
   
    docker-compose up -d
   
Check the status of the container :

    docker-compose ps
    
Check logs :

    docker-compose logs nginx
    docker-compose logs mysql
    docker-compose logs wordpress

## References

https://www.howtoforge.com/tutorial/dockerizing-wordpress-with-nginx-and-php-fpm/
