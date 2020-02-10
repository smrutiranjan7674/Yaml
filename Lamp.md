https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-ubuntu-18-04

1.sudo apt update
2.sudo apt install apache2
3.sudo systemctl restart apache2
4.sudo apt install php libapache2-mod-php php-mysql
5.sudo systemctl restart apache2
6.sudo nano /var/www/info.php
<?php
phpinfo();
?>

For RHEL
sudo yum install httpd
sudo systemctl start httpd.service
sudo systemctl enable httpd.service
sudo yum install php php-mysql
sudo systemctl restart httpd.service
sudo vi /var/www/html/info.php
<?php phpinfo(); ?>