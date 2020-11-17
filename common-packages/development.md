# development

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.3.0 (2020-10-23)


### build

* allow grunt scripts:lint:eslint --fix as option
* consider .ts files in webpack config


### chore

* enable eslint rule @typescript-eslint/consistent-type-imports
* merge tsconfig.json with backend-coding
* target ES6 in tsc


### feat

* route PATCH PaddleIncompleteOrder (#8ywfdu)
* route POST UserSession (#9erj57)


### refactor

* use "import type" instead of "import"





# 1.2.0 (2020-10-08)


### chore

* **release :** version bump


### feat

* file download link with TTL (#7jnqka)
* introduce real-commerce (#8ywen0)
* node Docker best practices (#7pqhjr)
* storge generates download URL for local cache (#8ep55j)


### fix

* order of .envDefault and .env exposing (#8ep55j)





# 1.1.0 (2020-09-29)


### build

* add grunt task to make JS pot files more conflict-resistent (#6utk9n)
* backend pot files and JSON generation conflict-resistent (#6utk9n)


### chore

* gitignore json language files for WP packages and plugins (#6utk9n)
* introduce development package (#6utk9n)
* move backend files to development package (#6utk9n)
* move grunt to common package (#6utk9n)
* move packages to development package
* move packages to development package (#6utk9n)
* move scripts to grunt scripts (#6utk9n)
* move some files to development package (#6utk9n)
* prepare package grunt scripts (#6utk9n)
* refactor backend package.json scripts (#6utk9n)
* remove grunt task aliases (#6utk9n)
* update dependencies (#3cj43t)
* update package.json script for WordPress packages (#6utk9n)
* update package.json scripts for each plugin (#6utk9n)


### ci

* initial jobs (#6utk9n)


### feat

* POST Company route and Superadmin guard (#7jnqb2)
