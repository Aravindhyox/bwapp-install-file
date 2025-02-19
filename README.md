# Install this php dependencies to prevent errors: 

apt install php 

apt install php-mysql

apt install php-gd



# On terminal: 

sudo pluma /etc/php/8.2/apache2/php.ini 

make change to "on" this lines  > 508 & 517 & 866 & 870. 



# To create bWAPP database :


create user 'bee'@'localhost' identified by 'bug';

grant all privileges on bWAPP.* to 'bee'@'localhost' identified by 'bug';

create database bWAPP;



# See full video tutorial :
# To read blog :
