# wordpressaws

Script provides an example of automating a WordPress installation on a newly commissioned EC2 instance. The script will perform the following actions.

- Update the base image
- Install Apache/MySQL/PHP
- Download and install the latest WordPress software
- Configure MySQL
- Configure wp-content.php and .htaccess accordingly

Change wordpressdb, wordpressuser and <wppassword> to new values.

Note: This leaves MySQL open after the installation. Please change the MySQL Root administrator password. Also, recommend that all proper AWS Secuirty Groups are setup correctly.


