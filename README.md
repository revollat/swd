sudo apt-get update

sudo apt-get install  php5-fpm php5-intl php5-curl php5-mysql nginx mysql-server phpmyadmin 

cd /etc/nginx/sites-available/ && sudo mv default sav.default

sudo cp ~/code/vhost /etc/nginx/sites-available/default

sudo service nginx reload
