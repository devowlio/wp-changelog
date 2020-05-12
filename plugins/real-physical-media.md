# real-physical-media

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.1.1 (2020-05-12)


### build

* cleanup temporary i18n files correctly


### fix

* correctly enqueue dependencies (#52jf92)





# 1.1.0 (2020-04-27)


### chore

* add hook_suffix to enqueue_scripts_and_styles function (#4ujzx0)


### docs

* update user documentation and redirect to help.devowl.io (#6c9urq)


### feat

* allow to enable / disable lowercase path (#4ar4pf)
* allow to transform special characters (#4ar3g1)
* improved installation process (#4ar07r)
* rewrite English translation and add German translation (#4aqkwf)


### fix

* compatibility with Redirection plugin (#4ar786)
* confirm first before clearing SEO redirects (#4rqhh0)
* deactivate / activate redirects in SEO dialog (#4rqhh0)
* do not reload page after changing guid and post_name length (#4rqhh0)
* initial queue after page load
* modify post_names and guid field in settings (#4rqhh0)
* move to queue in attachment media dialog reloads now correctly (#4rqhh0)
* notice could not be removed as non-admin
* show automatic queueing hint after first movement of files (#4ar6gz)
* show notice after activating a rename handler (#4aqz39)
* show queue popover when using the plugin for first time(#4aqz39)


### style

* add closeable X to popover (#4rqhh0)
* hide duration of processed items and database size in SEO dialog (#4rqhh0)
* list cronjob urls in readonly-input with copy functionality (#4ar47j)
* move handler picker to settings (#4rqhh0)
* overlapping arrow in queue popover (#4rqhh0)
* wordings in SEO dialog and settings (#4rqhh0)


### test

* add smoke tests (#4rm5ae)
* automatically retry cypress tests (#3rmp6q)





## 1.0.10 (2020-04-20)

**Note:** Version bump only for package @devowl-wp/real-physical-media





## 1.0.9 (2020-04-16)

**Note:** Version bump only for package @devowl-wp/real-physical-media





## 1.0.8 (2020-04-16)


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

* some wordings (#4grh8t)


### style

* move delay options to the bottom in settings (#4ar2ct)
* reformat php codebase (#4gg05b)


### test

* avoid session expired error in E2E tests (#3rmp6q)





## 1.0.7 (2020-03-31)


### chore

* show correct plugin author in plugins list
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





## 1.0.6 (2020-03-13)


### chore

* add link to support system in plugins list (#42jp1z)
* make ready for WordPress 5.4 release (#42g9wx)


### fix

* i18n is not correctly initialized





## 1.0.5 (2020-03-15)
- fix bug with deletion of thumbnail sizes by name with dashes
- fix bug with links in popover dialog

## 1.0.4 (2020-02-12)
- prepare for Real Media Library v4.6.0

## 1.0.3 (2020-02-11)
- prepare for Real Media Library v4.6.0
- fix root folder named "Unorganized"
- add filter RPM/Attachment/Folder/Path to modify complete physical path relative to uploads dir
- add filter RPM/Attachment/Folder/PathPart to modify a single physical path part relative to uploads dir

## 1.0.2 (2019-08-20)
- fix upload prefix when uploading to "All files"
- fix countdowns are not correctly applied
- fix uploading files via WP REST API or sideload

## 1.0.1 (2019-03-19)
- fix SEO redirects when accessing WP internals GUID url (for example Essential Grid)
- fix style/script dependencies

# 1.0.0 (2019-01-19)
- initial review
