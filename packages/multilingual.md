# multilingual

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.6.1 (2021-03-30)


### refactor

* use composer autoload to setup constants and package localization





# 1.6.0 (2021-03-23)


### chore

* **release :** publish [ci skip]


### feat

* introduce Weglot compatibility (CU-fd0cmc)


### fix

* array offset notice directly after installing WPML (CU-e8x3em)





## 1.5.1 (2021-02-24)


### chore

* introduce empty class for Weglot


### fix

* do not translate gettext texts with TranslatePress cause it adds some weired characters (CU-egxxjh)
* strip gettext texts for TranslatePress (CU-egxxjh)





# 1.5.0 (2021-02-16)


### feat

* introduce new function to iterate all language contexts
* introduce new Output Buffer plugins and TranslatePress compatibility (CU-cew7v9)


### fix

* add TranslatePress stub to translate a complete page
* compatibility with TranslatePress (CU-cew7v9)
* compatibility with WPML and PolyLang; defaults are not correctly created on installation (CU-e50f0d)


### perf

* do not translate JSON with TranslatePress, use single HTML string





# 1.4.0 (2021-02-02)


### feat

* introduce translations for output buffer plugins (TranslatePress, CU-dd4a3q)





## 1.3.5 (2021-01-24)


### refactor

* remove unused classes and methods





## 1.3.4 (2021-01-18)


### fix

* allow Show all languages in PolyLang and WPML (CU-cjyzay)





## 1.3.3 (2021-01-11)


### build

* reduce javascript bundle size by using babel runtime correctly with webpack / babel-loader


### chore

* **release :** publish [ci skip]
* **release :** publish [ci skip]


### fix

* wrong language for duplicated cookie when using PolyLang default language in admin dashboard





## 1.3.2 (2020-12-09)


### chore

* update to webpack v5 (CU-4akvz6)
* updates typings and min. Node.js and Yarn version (CU-9rq9c7)
* **release :** publish [ci skip]





## 1.3.1 (2020-12-01)


### chore

* update to composer v2 (CU-4akvjg)
* update to core-js@3 (CU-3cj43t)
* **release :** publish [ci skip]
* **release :** publish [ci skip]





# 1.3.0 (2020-10-23)


### feat

* route PATCH PaddleIncompleteOrder (#8ywfdu)





## 1.2.2 (2020-10-08)


### chore

* **release :** version bump





## 1.2.1 (2020-09-29)


### build

* backend pot files and JSON generation conflict-resistent (#6utk9n)


### chore

* introduce development package (#6utk9n)
* move backend files to development package (#6utk9n)
* move grunt to common package (#6utk9n)
* move packages to development package (#6utk9n)
* move some files to development package (#6utk9n)
* update dependencies (#3cj43t)
* update package.json script for WordPress packages (#6utk9n)





# 1.2.0 (2020-09-22)


### feat

* introduce LanguageDependingOption (#84mnnc)


### fix

* import settings (#82rk4n)
* use language for non-WPML pages in cookie / blockers presets cache key (#86wk0t)





## 1.1.1 (2020-08-20)


### fix

* improved content blocker with WPML / PolyLang (#6jggau)





# 1.1.0 (2020-08-17)


### feat

* introduce @devowl-wp/multilingual package (#4wqqym)





# 1.1.0 (2020-08-17)


### feat

* introduce @devowl-wp/multilingual package (#4wqqym)
