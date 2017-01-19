# DevShop Example Repository
## Makefiles in Git

Use this repository as an example for your project.

When creating your project, use "docroot" as your "Path to Drupal" (or choose your own. When using makefiles, this folder is the destintion of the drush make build.)

Use "drupal.make" as your "Path to Makefile".

Soon we will allow you to add a `.devshop.yml` file where you can set these properties directly in your project's codebase. 

## Editing your makefile

You can put anything in your makefile as long as it processes successfully.

Adding a "profile" will include that install profile and all dependencies.

You can include custom repositories now, and soon you will be able to include "local" code right in the same git repo.  (coming soon, pending a patch to Aegir & Drush).



