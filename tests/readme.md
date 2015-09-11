- composer install
- mysql: create wordpress_test;
- Run ./vendor/bin/phpunit



See coverage ./vendor/bin/phpunit --coverage-html=coverage


unit/includes/*.php files generated from

```
wp core install --path=./wordpress --url=example.com --title=testblog --admin_user=admin --admin_password=admin --admin_email=admin@example.com
```

and:

```
./bin/install-wp-tests.sh wordpress_test root ''
```