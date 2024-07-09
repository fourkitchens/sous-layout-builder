# Sous Layout Builder Drupal Recipe
A recipe that contains modules and configuration for Sous default layout builder configuration.

## Configuring Drupal for Recipes

See https://www.drupal.org/files/issues/2023-10-01/Configuring%20Drupal%20to%20Apply%20Recipes.md

## Installing this Recipe

`composer require fourkitchens/sous-layout-builder`

## Applying this Recipe

If you used the Sous Project as your starterkit:
- `lando install-recipe fourkitchens/sous-layout-builder`

Manually applying the recipe to your own project:
From your webroot run:
- `php core/scripts/drupal recipe recipes/sous-layout-builder`
- `drush cr`
- `composer unpack fourkitchens/sous-layout-builder`
