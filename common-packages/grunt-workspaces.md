# grunt-workspaces

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 0.1.1 (2021-05-11)


### build

* lerna exec should only run grunt scripts if they exist


### refactor

* extract prune dependencies to the backend package
* introduce eslint-config package
* introduce new grunt workspaces package for monolithic usage
* introduce new package to validate yarn licenses and generate disclaimer
* introduce new script to run-yarn-children commands
* move .env-default file to root folder
* move WP specific typescript config to @devowl-wp/wp-webpack package
* remove @devowl-wp/development package
