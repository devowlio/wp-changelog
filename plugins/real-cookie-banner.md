# real-cookie-banner

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 0.23.0 (2020-11-03)


### ci

* release to new license server (#8wpcr1)


### feat

* new cookie and blocker presets (Paddle.com, Google Analytics 4, SoundCloud, #9gqu4j)


### fix

* make http cookie host field required
* multiple creation of cookie templates in conflict with Consent Forwarding (#9mr2zh)





# 0.22.0 (2020-10-23)


### feat

* route PATCH PaddleIncompleteOrder (#8ywfdu)


### fix

* remove moment as it is not needed


### refactor

* use "import type" instead of "import"





# 0.21.0 (2020-10-16)


### build

* use node modules cache more aggressively in CI (#4akvz6)


### chore

* add Consent/Block/HTML developer filter
* introduce Real Product Manager WordPress client package (#8cxk67)
* remove unnecessery dependency
* update PUC (#8cxk67)


### feat

* add checklist in config page header (#8cxk67)
* announcements (#8cxk67)


### fix

* avoid issue with inifite loop when stats checklist item is unchecked
* enable old auto updater instead of new one for EA (#8cxk67)
* load blocker.js in footer (#96p6wf)
* more pages in imprint and privacy policy dropdown
* order pages by relevance in settings (imprint, privacy policy) (#96wu8n)
* review 1 (#8cxk67)
* review 2 (#8cxk67)
* review 3 (#8cxk67)
* review 4 (#8cxk67)
* use correct product id and variant id
* use inline style to reset parent container for content blocker due to theme conflicts (#94xp4g)
* validate response in PUC (#8cxk67)





# 0.20.0 (2020-10-14)


### feat

* allow to show cookie banner through admin bar in frontend again (#92w4h9)


### fix

* amazon widget cookie template (#94xfb1)
* compatibility blocker with WP Google Maps PRO (#94q9hu)
* compatibility of WordPress comments blocker with more themes (#94y5vh)
* compatibility with WP Fastest Cache (#94xk58)
* compatibility with WP Google Maps PRO (#94q9hu)
* content blocker parent element height and scrolling issues (#94xp4g)
* edit capabilities (#96r2xb)
* use native mysql functions for exporting consents (#90x0cv)





## 0.19.2 (2020-10-13)


### chore

* **release :** publish [ci skip]


### fix

* download consent CSV (#90x0cv)
* google maps blocker compatibility with WP Google Maps plugin (#94q9hu)


### test

* add smoke tests (#84ukve)





## 0.19.1 (2020-10-12)


### fix

* google analytics template tracking ID pattern (#92wpck)





# 0.19.0 (2020-10-09)


### feat

* add cross-selling for Real Cookie Banner (#4rrt0d)


### fix

* enqueue utils in Real Cookie Banner to make cross-selling work





# 0.18.0 (2020-10-08)


### chore

* **release :** version bump


### feat

* review two user tests, added VG WORT preset (#8wx249)


### fix

* google maps blocker preset now supports german URLs (#8ywmwe)





# 0.17.0 (2020-09-29)


### build

* backend pot files and JSON generation conflict-resistent (#6utk9n)


### chore

* introduce development package (#6utk9n)
* move backend files to development package (#6utk9n)
* move grunt to common package (#6utk9n)
* move packages to development package (#6utk9n)
* move scripts to grunt scripts (#6utk9n)
* move some files to development package (#6utk9n)
* remove grunt task aliases (#6utk9n)
* update dependencies (#3cj43t)


### feat

* faq in wordpress.org description (#8ew590)





## 0.16.2 (2020-09-23)


### fix

* serve anti-ad-blocker script correctly after cache rebuild (#8er103)





## 0.16.1 (2020-09-22)


### ci

* correctly push to try.devowl.io (#7ppr38)


### fix

* correctly determine cookie presets for try.devowl.io (#7ppr38)





## 0.16.1 (2020-09-22)


### ci

* correctly push to try.devowl.io (#7ppr38)


### fix

* correctly determine cookie presets for try.devowl.io (#7ppr38)
