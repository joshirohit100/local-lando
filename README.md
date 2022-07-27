# local-lando
Allows to setup and run drupal project locally 


# Steps
 - Create the project `composer create-project --no-interaction acquia/drupal-recommended-project YOUR_DIRECTORY_NAME_HERE` or You can use the drupal project template <link>https://www.drupal.org/docs/develop/using-composer/manage-dependencies#s-create-a-project<link>
 - Add this `.lando.yml` file to your project root directory
 - Adjust the `webroot` in `.lando.yml` according to your project
 - Adjust the database `portforward` accordignly if required as this port will be used for database connection
 - Run `lando start` to initiate the container creation
 - Run `lando info` to check the info
