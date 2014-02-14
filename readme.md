The real module made by 
https://drupal.org/project/composer_manager

I needed to stop it trying to run updates on every enable disable so I could use
/usr/bin/composer --working-dir=/var/www/site/current/sites/default/files/composer install
instead which took less memory and time

I still use
drush composer-rebuild-file to setup the composer.json file as needed


