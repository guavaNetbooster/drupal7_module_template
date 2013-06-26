# NetBooster Drupal 7 Module Template

## [module_name].module
Main module file. Hooks are implemented using the following pattern:
- [module_name]_[hook name]

A module called "foo", needing to use the hook "hook_bar_baz" would create the following function:
- function foo_bar_baz(...)

Note that even though "hook" is part of the hook name in the documentation, it should not be included 
in the function name. The list of parameters depend on the hook.

## [module_name].install
Install and uninstall hooks.

## [module_name].info
Module Name meta data and setup (css, js, dependencies, ...)<br />
[Drupal 7 .info properties](https://drupal.org/node/542202)