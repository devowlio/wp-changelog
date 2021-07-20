# search-engine-post-type

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.4.4 (2021-07-20)

**Note:** Version bump only for package @devowl-wp/search-engine-post-type





## 1.4.3 (2021-05-25)


### chore

* migarte loose mode to compiler assumptions





## 1.4.2 (2021-05-11)


### chore

* remove fork of algoliasearch-client-php


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





## 1.4.1 (2021-03-02)


### fix

* calculate permalink at runtime instead of storing it in index record (CU-eyzgf0)





# 1.4.0 (2021-02-16)


### chore

* initial commit (CU-agv00d)
* scope algolia search package correctly with a forked Git repository


### docs

* update README for basic usage


### feat

* add Algolia search for knowledgebase and implement in support form (CU-agv00d)
* allow to change search attributes and slugs via callback
* introduce search engine quota (CU-agv00d)


### fix

* compatibility with page builder WPBakery (CU-agv00d)
* compatibility with TranslatePress (CU-cew7v9)
* correctly sanitize post content with all allowed HTML tags


### test

* do not exit script when running WP CLI and no Algolia key is defined
