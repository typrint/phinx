# [Phinx](https://phinx.org): Simple PHP Database Migrations

[![Build Status](https://github.com/typrint/phinx/workflows/CI/badge.svg?branch=0.x&event=push)](https://github.com/typrint/phinx/actions?query=workflow%3A%22CI%22+branch%3A0.x+event%3Apush)
[![Code Coverage](https://codecov.io/gh/typrint/phinx/branch/master/graph/badge.svg)](https://codecov.io/gh/typrint/phinx)
![Packagist Version](https://img.shields.io/packagist/v/typrint/phinx)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%208.1-8892BF.svg)](https://php.net/)
![Packagist Downloads](https://img.shields.io/packagist/dt/typrint/phinx)

## Intro

Phinx makes it ridiculously easy to manage the database migrations for your PHP app. In less than 5 minutes, you can install Phinx and create your first database migration. Phinx is just about migrations without all the bloat of a database ORM system or framework.

**Check out [book.cakephp.org/phinx](https://book.cakephp.org/phinx) for the comprehensive documentation.**

![phinxterm](https://cloud.githubusercontent.com/assets/178939/3887559/e6b5e524-21f2-11e4-8256-0ba6040725fc.gif)

### Features

* Write database migrations using database agnostic PHP code.
* Migrate up and down.
* Migrate on deployment.
* Seed data after database creation.
* Get going in less than 5 minutes.
* Stop worrying about the state of your database.
* Take advantage of SCM features such as branching.
* Integrate with any app.

### Supported Adapters

Phinx natively supports the following database adapters:

* MySQL
* PostgreSQL
* SQLite
* Microsoft SQL Server

## Install & Run

### Composer

The fastest way to install Phinx is to add it to your project using Composer (https://getcomposer.org/).

1. Install Composer:

    ```
    curl -sS https://getcomposer.org/installer | php
    ```

1. Require Phinx as a dependency using Composer:

    ```
    php composer.phar require typrint/phinx
    ```

## Documentation

Check out https://book.cakephp.org/phinx for the comprehensive documentation.

Other translations include:

 * [Chinese](https://tsy12321.gitbooks.io/phinx-doc/) (Maintained by [@tsy12321](https://github.com/tsy12321/phinx-doc))

## Limitations

### PostgreSQL

- Not able to set a unique constraint on a table (<https://github.com/typrint/phinx/issues/1026>).

## Misc

### Version History

Please read the [release notes](https://github.com/typrint/phinx/releases).

### License

MIT
