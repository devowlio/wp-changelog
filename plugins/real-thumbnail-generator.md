# real-thumbnail-generator

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 2.5.8 (2021-05-12)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.5.7 (2021-05-11)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.5.6 (2021-05-11)


### chore

* **release :** publish [ci skip]


### ci

* push plugin artifacts to GitLab Generic Packages registry (CU-hd6ef6)


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
* move technical doc scripts to proper WP and backend package
* move WP build process to @devowl-wp/utils
* move WP i18n scripts to @devowl-wp/utils
* move WP specific typescript config to @devowl-wp/wp-webpack package
* remove @devowl-wp/development package
* split stubs.php to individual plugins' package





## 2.5.5 (2021-03-30)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.5.4 (2021-03-23)


### build

* plugin tested for WordPress 5.7 (CU-f4ydk2)





## 2.5.3 (2021-03-10)


### fix

* properly detect thumbnail size for PDFs and images





## 2.5.2 (2021-03-02)


### fix

* respect language of newsletter subscriber to assign to correct newsletter (CU-aar8y9)





## 2.5.1 (2021-02-24)


### chore

* rename go-links to new syntax (#en621h)


### docs

* rename test drive to sanbox (#ef26y8)


### fix

* compatibility with GS Only PDF Preview plugin (CU-epzbcn)





# 2.5.0 (2021-02-16)


### chore

* improve UX after user tests (CU-devznm)


### docs

* update README to be compatible with Requires at least (CU-df2wb4)


### feat

* improve English translation (#devznm)
* improve English translation (#devznm)
* translation into German (#devznm)


### fix

* verify settings with error messages (CU-devznm)
* when uploading a file in Add New page a notice was thrown (CU-devznm)





## 2.4.12 (2021-02-02)


### chore

* remove limit for regenerations (CU-d6z2u6)


### docs

* improved product description for wordpress.org (#d6z2u6)





## 2.4.11 (2021-01-24)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.10 (2021-01-11)


### build

* reduce javascript bundle size by using babel runtime correctly with webpack / babel-loader


### chore

* **release :** publish [ci skip]
* **release :** publish [ci skip]





## 2.4.9 (2020-12-15)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.8 (2020-12-10)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.7 (2020-12-09)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.6 (2020-12-09)


### chore

* update to cypress v6 (CU-7gmaxc)
* update to webpack v5 (CU-4akvz6)
* updates typings and min. Node.js and Yarn version (CU-9rq9c7)
* **release :** publish [ci skip]


### fix

* automatically deactivate lite version when installing pro version (CU-5ymbqn)





## 2.4.5 (2020-12-01)


### chore

* update dependencies (CU-3cj43t)
* update major dependencies (CU-3cj43t)
* update to composer v2 (CU-4akvjg)
* update to core-js@3 (CU-3cj43t)
* **release :** publish [ci skip]


### fix

* compatibility with react-responsive-modal (CU-3cj43t)


### refactor

* enforce explicit-member-accessibility (CU-a6w5bv)





## 2.4.4 (2020-11-24)


### fix

* compatibility with upcoming WordPress 5.6 (CU-amzjdz)
* use no-store caching for WP REST API calls to avoid issues with browsers and CloudFlare (CU-agzcrp)





## 2.4.3 (2020-11-18)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.2 (2020-11-17)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.4.1 (2020-11-12)


### ci

* make scripts of individual plugins available in review applications (#a2z8z1)
* release to new license server (#8wpcr1)





# 2.4.0 (2020-10-23)


### feat

* route PATCH PaddleIncompleteOrder (#8ywfdu)


### refactor

* use "import type" instead of "import"





## 2.3.9 (2020-10-16)


### build

* use node modules cache more aggressively in CI (#4akvz6)


### chore

* rename folder name (#94xp4g)





## 2.3.8 (2020-10-09)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.3.7 (2020-10-08)


### chore

* **release :** version bump





## 2.3.6 (2020-09-29)


### build

* backend pot files and JSON generation conflict-resistent (#6utk9n)


### chore

* introduce development package (#6utk9n)
* move backend files to development package (#6utk9n)
* move grunt to common package (#6utk9n)
* move packages to development package (#6utk9n)
* move some files to development package (#6utk9n)
* remove grunt task aliases (#6utk9n)
* update dependencies (#3cj43t)
* update package.json scripts for each plugin (#6utk9n)





## 2.3.5 (2020-09-22)


### fix

* import settings (#82rk4n)





## 2.3.4 (2020-08-31)


### fix

* change of software license from GPLv3 to GPLv2 due to Envato Market restrictions (#4ufx38)





## 2.3.3 (2020-08-26)


### chore

* **release :** publish [ci skip]


### ci

* install container volume with unique name (#7gmuaa)


### perf

* remove transients and introduce expire options for better performance (#7cqdzj)





## 2.3.2 (2020-08-17)


### ci

* prefer dist in composer install


### fix

* delete unused wasnt executed correctly





## 2.3.1 (2020-08-11)


### chore

* backends for monorepo introduced





# 2.3.0 (2020-07-30)


### feat

* introduce dashboard with assistant (#68k9ny)
* WordPress 5.5 compatibility (#6gqcm8)


### fix

* option to force new schema
* REST API notice in admin dashboard
* toggle to show only errors





## 2.2.1 (2020-07-02)


### chore

* allow to define allowed licenses in root package.json (#68jvq7)
* update dependencies (#3cj43t)


### test

* cypress does not yet support window.fetch (#5whc2c)





# 2.2.0 (2020-06-17)


### chore

* added two new filters for developers RTG/Regenerate/Path and RTG/Regenerate/AbsolutePath (#5yk9nj)
* update plugin updater newsletter text (#6gfghm)


### feat

* allow to use ID as placeholder (#5yk9at)





## 2.1.6 (2020-06-12)


### chore

* i18n update (#5ut991)





## 2.1.5 (2020-05-27)


### build

* improve plugin build with webpack parallel builds


### ci

* use hot cache and node-gitlab-ci (#54r34g)


### docs

* redirect user documentation to new knowledgebase (#5etfa6)





## 2.1.4 (2020-05-20)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.1.3 (2020-05-14)


### docs

* link to free test drive in wordpress.org description





## 2.1.2 (2020-05-14)


### docs

* new wordpress.org assets #6jbg2r





## 2.1.1 (2020-05-12)


### build

* cleanup temporary i18n files correctly


### fix

* correctly enqueue dependencies (#52jf92)





# 2.1.0 (2020-04-27)


### chore

* add hook_suffix to enqueue_scripts_and_styles function (#4ujzx0)


### docs

* update user documentation and redirect to help.devowl.io (#6c9urq)


### feat

* rewrite English translation and add German translation (#4aqkwf)


### test

* add smoke tests (#4rm5ae)
* automatically retry cypress tests (#3rmp6q)





## 2.0.14 (2020-04-20)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.0.13 (2020-04-16)

**Note:** Version bump only for package @devowl-wp/real-thumbnail-generator





## 2.0.12 (2020-04-16)


### build

* adjust legal information for envato pro version (#46fjk9)
* move test namespaces to composer autoload-dev (#4jnk84)
* reduce bundle size by ~25% (#4jjq0u)
* scope PHP vendor dependencies (#4jnk84)


### chore

* create real-ad package to introduce more UX after installing the plugin (#1aewyf)
* rename real-ad to real-utils (#4jpg5f)
* update to Cypress v4 (#2wee38)


### ci

* correctly build i18n frontend files (#4jjq0u)
* run package jobs also on devops changes


### fix

* limit bulk-regeneration in lite version to 300 images (#4akhnt)
* undefined index notice (#4gkt3j)


### style

* reformat php codebase (#4gg05b)


### test

* avoid session expired error in E2E tests (#3rmp6q)





## 2.0.11 (2020-03-31)


### chore

* update dependencies (#3cj43t)
* **release :** publish [ci skip]
* **release :** publish [ci skip]
* **release :** publish [ci skip]


### ci

* use concurrency 1 in yarn disclaimer generation


### style

* run prettier@2 on all files (#3cj43t)


### test

* configure jest setupFiles correctly with enzyme and clearMocks (#4akeab)
* generate test reports (#4cg6tp)





## 2.0.10 (2020-03-13)


### chore

* make ready for WordPress 5.4 release (#42g9wx)


### fix

* i18n is not correctly initialized





## 2.0.9 (2020-03-05)


### build

* chunk vendor libraries (#3wkvfe) and update antd@4 (#3wnntb)


### chore

* update dependencies (webpack, types)





## 2.0.8 (2020-02-27)


### docs

* CHANGELOG and README





## 2.0.7 (2020-02-26)


### fix

* compatibility running Real Media Library and Real Thumbnail Generator together (hotfix)





## 2.0.6 (2020-02-26)


### build

* add exclude-from-classmap for freemium package (#3rgyt1)
* asset is not correctly enqueued (#3rgyt1)
* migrate real-thumbnail-generator to monorepo
* prepare lite version for further usage (#3rgyt1)


### docs

* exclude-from-classmap (#3rgyt1)


### fix

* make more compatible with WP 5.3 (#3upazm)
* only this sizes works now as expected (#3upazm)
* thumbnails are now correctly deleted in wp-content/uploads (#3upazm)
* update urls to devowl.io (#3rgyt1)





## 2.0.5 (2019-10-07)

* fix bug with thumbnails path when using %size-identifier%
* fix bug with 503er server errors and retry regenerate again

## 2.0.4 (2019-08-21)

* add search by filename in Analyse / Regenerate tab
* fix bug with WooCommerce thumbnails and custom cropping
* improve error handling so the process does not stop when an error occurs
* improve performance by only loading images when hovering in analyse item
* improve performance by list virtualization
* improve height of opened analyse dialog

## 2.0.3 (2019-08-09)

* fix bug with page reload in "Edit attachment" page
* fix bug while error is logged when opening an attachment in the dialog
* fix bug when attachment is deleted and shows still as "Unused"
* improve regeneration list that now all items are clickable
* released lite version

## 2.0.2 (2019-03-19)

* fix bug with style/script dependencies

## 2.0.1 (2019-02-21)

* the plugin is now fully compatible with Crop-Thumbnails plugin
* fix bug with Internet Explorer
* fix bug with icons
* fix bug with PDFs

# 2.0.0 (2019-02-15)

* complete code rewrite, same functionality with improve performance, with an eye on smooth user interface and experience
* add option to skip existing thumbnail files
* add autoupdater functionality in Plugins > "License settings"
* add checbox to select / deselect all registered thumbnail sizes
* fix bug with generation of single thumbnail sizes
* fix compatibility with Simple Matted Thumbnails
* fix compatibility with EWWW Image Optimizer
* improve performance and usability

## 1.1.7 (2018-03-23)

* add "Regenerate" button to PDF files in list view
* fix bug with PDF thumbnails while getting "-1" prefix

## 1.1.6 (2018-03-22)

* fix bug with PDF generation in thumbnail folders
* fix bug with deletion of old thumbnails when changing the thumbnails schema
* fix bug with deletion of empty thumbnail folders

## 1.1.5 (2017-10-10)

* fix bug with duplicate info containers about thumbnails

## 1.1.4 (2017-05-25)

* add option to set a chunk size for regeneration

## 1.1.3 (2017-04-14)

* fix bug with SVG images

## 1.1.2 (2017-03-17) #

* fix bug with AJAX Search Pro
* fix bug with Facebook hint in plugins site

## 1.1.1 (2017-01-04)

* fix bug with failed thumbnail sizes
* fix bug with .txt upload
* fix bug with regenerating only a set of sizes

# 1.1.0 (2016-12-09)

* add ability to regenerate only specific image sizes
* fix bug with copped image sizes

## 1.0.1 (2016-11-29)

* add the MatthiasWeb promotion dialog

# 1.0 (2016-11-10)

* initial review
