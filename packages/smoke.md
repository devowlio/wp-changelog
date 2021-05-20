# smoke

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.2.3 (2021-05-20)


### chore

* upgrade dependencies to latest minor version


### test

* make window.fetch stubbable (CU-jh3cza)
* run smoke tests also for chore/patch branches





## 1.2.2 (2021-05-11)


### refactor

* introduce eslint-config package
* introduce new grunt workspaces package for monolithic usage
* introduce new package to validate composer licenses and generate disclaimer
* introduce new package to validate yarn licenses and generate disclaimer
* move WP build process to @devowl-wp/utils
* move WP specific typescript config to @devowl-wp/wp-webpack package
* remove @devowl-wp/development package





## 1.2.1 (2020-12-09)


### chore

* update to cypress v6 (CU-7gmaxc)
* updates typings and min. Node.js and Yarn version (CU-9rq9c7)


### fix

* typing error from Node 14 upgrade (CU-9rq9c7)


### test

* fix viewport height
* run smoke tests also on wordpress branch (CU-7gmaxc)





# 1.2.0 (2020-10-23)


### feat

* route PATCH PaddleIncompleteOrder (#8ywfdu)


### refactor

* use "import type" instead of "import"





## 1.1.3 (2020-10-08)


### chore

* **release :** version bump





## 1.1.2 (2020-09-29)


### chore

* introduce development package (#6utk9n)
* move packages to development package (#6utk9n)
* update dependencies (#3cj43t)
* update package.json script for WordPress packages (#6utk9n)





## 1.1.1 (2020-09-22)


### fix

* import settings (#82rk4n)





# 1.1.0 (2020-07-30)


### feat

* introduce dashboard with assistant (#68k9ny)





## 1.0.3 (2020-07-02)


### chore

* update dependencies (#3cj43t)


### test

* cypress does not yet support window.fetch (#5whc2c)





## 1.0.2 (2020-06-12)


### chore

* broken NPM script
* move plugin/rcb branch to develop


### ci

* use hot cache and node-gitlab-ci (#54r34g)





## 1.0.1 (2020-04-27)


### ci

* remove detached mege request pipeline


### test

* add smoke tests (#4rm5ae)
* automatically retry cypress tests (#3rmp6q)
