# Drupal 8 Lando

Install the dependencies.

```sh
$ git clone repo
$ cd repo
$ lando start
$ lando composer install 
$ lando db-import drupal8.2020-03-21-1584833500.sql.gz
$ lando drush cr
```

Login on drupal

```sh
$ lando drush uli
```
