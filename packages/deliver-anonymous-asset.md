# deliver-anonymous-asset

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 0.1.5 (2021-06-05)


### fix

* warning in customizer when a handle can not be enqueued





## 0.1.4 (2021-05-25)


### chore

* migarte loose mode to compiler assumptions





## 0.1.3 (2021-05-11)


### ci

* validate eslint


### refactor

* create wp-webpack package for WordPress packages and plugins
* introduce eslint-config package
* introduce new grunt workspaces package for monolithic usage
* introduce new package to validate composer licenses and generate disclaimer
* introduce new package to validate yarn licenses and generate disclaimer
* introduce new script to run-yarn-children commands
* move build scripts to proper backend and WP package
* move jest scripts to proper backend and WP package
* move PHP Unit bootstrap file to @devowl-wp/utils package
* move PHPUnit and Cypress scripts to @devowl-wp/utils package
* move WP build process to @devowl-wp/utils
* move WP i18n scripts to @devowl-wp/utils
* move WP specific typescript config to @devowl-wp/wp-webpack package
* remove @devowl-wp/development package





## 0.1.2 (2021-02-24)


### fix

* automatically recreate random assets on plugin update
* correctly serve as HTTPS if requested over HTTPS
* in some edge cases the wordpress autoupdater does not fire the wp action and dynamic javascript assets are not generated





## 0.1.1 (2021-02-05)


### chore

* introduce new package @devowl-wp/deliver-anonymous-asset (CU-dgz2p9)


### fix

* remove anonymous javascript files on uninstall (CU-dgz2p9)
