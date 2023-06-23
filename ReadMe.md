#The initial Drupal Setup with DDEV see:https://ddev.readthedocs.io/en/latest/users/quickstart/

`ddev config --project-type=drupal10 --docroot=web --create-docroot
ddev start
ddev composer create drupal/recommended-project
ddev composer require drush/drush
ddev drush site:install --account-name=admin --account-pass=admin -y
ddev drush uli
ddev launch`
