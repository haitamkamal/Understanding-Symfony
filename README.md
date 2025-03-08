# Understanding-Symfony
# Start the Symfony Server
symfony server:start
# Install Twing
composer require symfony/twig-bundle
# Generate a Controller
php bin/console make:controller
# Generate an Entity
php bin/console make:entity
# Migrations
## Install Doctrine Migrations Bundle
composer require doctrine/doctrine-migrations-bundle
## Create a Migration
php bin/console make:migration
#  apply pending migrations to your database in Symfony. 
php bin/console doctrine:migrations:migrate
# php bin/console doctrine:fixtures:load
## Doctrine Fixtures are used to populate your database with initial data
# php bin/console doctrine:dbal:run-sql "SELECT * FROM your_table"
The php bin/console doctrine:dbal:run-sql command allows you to run raw SQL queries directly on your database in a Symfony project.
