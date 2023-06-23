#The initial Drupal Setup with DDEV see:https://ddev.readthedocs.io/en/latest/users/quickstart/

1.`ddev config --project-type=drupal10 --docroot=web --create-docroot`
2.`ddev start`
3.`ddev composer create drupal/recommended-project`
4.`ddev composer require drush/drush`
5.`ddev drush site:install --account-name=admin --account-pass=admin -y`
6.`ddev drush uli`
7.`ddev launch`
