# Setting Up Wordpress on koding.com

### Install MySQL
kpm install mysql

### Install Wordpress
kpm install wordpress

Add the following to wp-config
/** Stop WordPress from asking for FTP credentials */
define('FS_METHOD', 'direct');

### Installing