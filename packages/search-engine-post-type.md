# search-engine-post-type

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.4.2 (2021-04-29)


### refactor

* create wp-webpack package for WordPress packages and plugins





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
