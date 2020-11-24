# real-cookie-banner

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.1.1 (2020-11-24)


### fix

* compatibility with RankMath SEO
* do not block content in beaver builder edit mode (CU-agzcrp)
* do not output rcb calc time in json content type responses (Beaver Builder compatibility, CU-agzcrp)





# 1.1.0 (2020-11-24)


### docs

* add MS Clarity in README


### feat

* new cookie preset Google Trends (CU-ajrchu)
* new cookie preset Microsoft Clarity (#a8rv4x)


### fix

* allow document.write for unblocked scripts (#ajrchu)
* compatibility with upcoming WordPress 5.6 (CU-amzjdz)
* decode HTML entities in content blocker scripts, e.g. old Google Trends embed (#ajrchu)
* ensure banner overlay is always a children of document.body (CU-agz6u3)
* ensure banner overlay is always a children of document.body (CU-agz6u3)
* modify Google Trends to work with older embed codes (CU-ajrchu)
* modify max index length for MySQL 5.6 databases so all database tables get created (CU-agzcrp)
* multiple content blockers should be inside a blocking wrapper (CU-ajrchu)
* order with multiple content blocker scripts (#ajrchu)
* typo in german translation (CU-agzcrp)
* update Jetpack Site Stats and Comments content blocker (CU-amr3f1)
* use no-store caching for WP REST API calls to avoid issues with browsers and CloudFlare (CU-agzcrp)
* using multiple ads with Google Adsense (CU-ajrcn2)
* wrong cookie count for first time usage in dashboard (CU-agzcrp)





## 1.0.4 (2020-11-19)

**Note:** Version bump only for package @devowl-wp/real-cookie-banner





## 1.0.3 (2020-11-18)


### fix

* add Divi maps block to Google Maps content blocker
* banner not shown up in Happy Wedding Day theme
* compatibility with Divi Maps block





## 1.0.2 (2020-11-17)


### fix

* do not show licensing tab in free test drive (#acypm6)





## 1.0.1 (2020-11-17)


### ci

* wrong license.devowl.io package.json


### docs

* wordpress.org README


### fix

* remove unnecessary dependency (composer) package (#acwy1g)





# 1.0.0 (2020-11-17)


### chore

* initial release (#4rruvq)


### test

* fix lite version smoke tests
* fix smoke test
* fix smoke tests for lite version
* fix typo in lite smoke test


* chore!: remove early access notice for newer updates (#4rruvq)
* feat!: use new license server (#4rruvq)
* ci!: release free version to wordpress.org automatically (#4rruvq)


### BREAKING CHANGE

* we are live!
* if you were a early access user, please upgrade to the initial version
* you need to enter your license key again to get automatic updates
* download initial version now here: https://wordpress.org/plugins/real-cookie-banner
