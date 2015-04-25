## インストール手順

```
# composer install
curl -sS https://getcomposer.org/installer | php
php composer.phar install

# setting database
cp app/Config/database.php.default app/Config/database.php
vi app/Config/database.php # change database login password 

# build in server
php -S localhost:8111 -t app/webroot/
```

