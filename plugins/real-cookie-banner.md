# real-cookie-banner

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.16.0 (2020-09-22)


### ci

* correctly update RCB in license.devowl.io (#8crb19)


### feat

* allow muliple content blocker presets in cookie presets (#8cv69e)


### fix

* block specific functionality on try.devowl.io (#7ppr38)





# 0.15.0 (2020-09-22)


### chore

* fix bundle size
* show notice when early-access phase expires (#84ufbx)


### docs

* add GIF screenshots to wordpress.org README (#4rru6v)


### feat

* add welcome-page GIFs (#4rru6v)
* description, banner und icon for wp.org (#4ufx1u)
* introduce LanguageDependingOption (#84mnnc)
* key feature texts (#4rru6v)
* notice if a opt-in script is not necessary (#86wk0t)
* notice if user should remove old service injection (#86wk0t)
* translations (#86wk0t)


### fix

* add default option values in WPML / PolyLang scenario (#82wb1q)
* add default option values only for default content procedure (#82wb1q)
* bug with empty response for blocker script (#86wk0t)
* consent unique name error when editing a cookie
* correctly add_option in admin_init hook (#82wb1q)
* correctly add_option in non-REST hook (#82wb1q)
* custom element blocker should also allow blocking scripts (#82w489)
* do not track causes issues in firefox (#84uvth)
* do only clear output buffer if needed (#82r05x)
* expose consentAPI (#88t8tz)
* import settings (#82rk4n)
* latest changes for go live devowl.io (#7uwhgz)
* localize redirection link for PRO version (#7ute3a)
* move age notice below duration of cookie consent setting (#82ruqq)
* remove urldecode as it is no longer needed
* review 1 (#84uw95)
* review 1 (#86wk0t)
* review 2 (#86wk0t)
* review 3 (#86wk0t)
* review 4 (#86wk0t)
* scroll container in first view of cookie banner
* several bugs before go live on devowl.io
* spelling mistake in welcome page (#82uwh1)
* spelling mistakes
* usage with PolyLang Free and WP REST API (#82v0t7)
* use -pro slug (#82rgxu)
* use correct slug in local environment for auto-updater
* use language for non-WPML pages in cookie / blockers presets cache key (#86wk0t)
* use placeholders in key features (#4rru6v)





# 0.14.0 (2020-09-08)


### feat

* introduce upselling dialog (#6pmcqx)


### fix

* import PRO features (#68tee7)
* review 1 (#68tee7)
* review 2 (#68tee7)
* review 2 (#6utam1)
* review 3 (#68tee7)
* use correct links in PRO badges (#6pmcqx)





# 0.13.0 (2020-08-31)


### build

* use correct LICENSE file in free and pro version (#7rn9ua)


### docs

* license (#4ufx38)


### feat

* add font weight to customize (#6mtdrg)
* ePrivacy note in customize and frontend (#6utam1)
* introduce settings for ePrivacy note (#6utam1)


### fix

* move state of option to context and add in list of consents (#6utam1)
* review 1 (#6utam1)
* use uuid from other consent contexts as well (#7pq9yw)





# 0.12.0 (2020-08-28)


### feat

* add form content blocker (#7anvaz)
* add legacy update server for early-access program (#7mvqnd)


### fix

* do not capture scripts in inline scripts
* finalize form content blocker (#7anvaz)
* non-context cookie name causes issues (#7pp5k1)
* register options autoload in plugins init hook (#74t83a)





# 0.12.0 (2020-08-28)


### feat

* add form content blocker (#7anvaz)
* add legacy update server for early-access program (#7mvqnd)


### fix

* do not capture scripts in inline scripts
* finalize form content blocker (#7anvaz)
* non-context cookie name causes issues (#7pp5k1)
* register options autoload in plugins init hook (#74t83a)
