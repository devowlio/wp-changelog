# real-cookie-banner

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 1.4.2 (2021-01-11)


### fix

* in some edge cases WP Rocket does blockage twice (CU-ccvvdn)





## 1.4.1 (2021-01-11)


### fix

* hotfix to make presets available again





# 1.4.0 (2021-01-11)


### build

* reduce javascript bundle size by using babel runtime correctly with webpack / babel-loader


### chore

* translate new cookie and blocker presets and register
* **release :** publish [ci skip]
* **release :** publish [ci skip]


### ci

* automatically activate PRO version in review application (CU-hatpe6)


### docs

* update README (CU-bevae9)


### feat

* new cookie and content blocker preset ActiveCampaign forms and site tracking (CU-bh04kz)
* new cookie and content blocker preset Discord (CU-c6vmgg)
* new cookie and content blocker preset MyFonts.net (CU-cawhga)
* new cookie and content blocker preset Proven Expert (Widget) (CU-cawhfp)
* new cookie preset Elementor (CU-cawhdk)
* new cookie preset Mouseflow (CU-cawj3n)
* new cookie preset Userlike (CU-cawhr3)


### fix

* apply gzip compression on the fly to the anti-ad-block system (CU-bx0am1)
* compatibility with All In One WP Security & Firewall (CU-bh08zp)
* compatibility with Facebook for WooCommerce plugin (CU-bwwwrt)
* compatibility with Meks Easy Photo Feed Widget Instagram feed (CU-bx0wd7)
* compatibility with Oxygen page builder
* compatibility with video and audio shortcode (CU-bt21kd)
* compatibility with youtu.be domain in YouTube content blocker preset (CU-bt21hp)
* compatiblity with WP Rocket lazy loading inline scripts (CU-bwwwrt)
* compatiblity with WP Rocket lazy loading YouTube videos (CU-byw6ua)
* content blocker for video and audio tags in some edge cases
* cookie preset selector busy indicator (CU-a8x3j0)
* generate dependency map for translations
* jquery issue when not in use (jQuery is now optional for RCB)
* use correct stubs for PolyLang


### perf

* preset PHP classes are only loaded when needed (CU-a8x3j0)
* speed up caching of presets (CU-a8x3j0)


### style

* input text fields in config page (CU-a8x3j0)





# 1.3.0 (2020-12-15)


### chore

* introduce custom powered-by link in PRO version (CU-b8wzqu)


### feat

* introduce rcb-consent-print-uuid shortcode (CU-bateay)
* new cookie and content blocker preset AddThis (CU-beva7q)
* new cookie and content blocker preset AddToAny (CU-beva7q)
* new cookie and content blocker preset Anchor.fm (CU-beva7q)
* new cookie and content blocker preset Apple Music (CU-beva7q)
* new cookie and content blocker preset Bing Maps (CU-beva7q)
* new cookie and content blocker preset reddit (CU-beva7q)
* new cookie and content blocker preset Spotify (CU-beva7q)
* new cookie and content blocker preset TikTok (CU-beva7q)
* new cookie and content blocker preset WordPress Emojis (CU-beva7q)


### fix

* block sandbox attribute for iframes (CU-beva7q)
* compatibility with WP External Links icon in banner and blocker footer (CU-bew81p)
* dashboard in lite version scrolls automatically to bottom (CU-bez8qn)
* list of consents does not expand if not initially saved settings once before
* memory error while reading the consent list (CU-9yzhrr)
* show ePrivacy and age notice even without description in visual content blocker (CU-beurgy)


### refactor

* introduce code splitting to reduce config page JavaScript assets (CU-b10ahe)





## 1.2.4 (2020-12-10)

**Note:** Version bump only for package @devowl-wp/real-cookie-banner





## 1.2.3 (2020-12-09)

**Note:** Version bump only for package @devowl-wp/real-cookie-banner





## 1.2.2 (2020-12-09)


### build

* use correct pro folders in build folder (CU-5ymbqn)


### chore

* update to cypress v6 (CU-7gmaxc)
* update to webpack v5 (CU-4akvz6)
* updates typings and min. Node.js and Yarn version (CU-9rq9c7)


### fix

* anonymous localized script settings to avoid incompatibility with WP Rocket lazy execution (CU-b4rp51)
* automatically deactivate lite version when installing pro version (CU-5ymbqn)
* compatibility with WP External Links (CU-b8w6yv)
* validate cookie host according to RFC 1123 instead of RFC 952 (CU-b31nf0)


### test

* smoke tests for Real Cookie Banner PRO





## 1.2.1 (2020-12-05)


### fix

* sometimes the privacy and imprint link are not correctly redirected (CU-b2x8wp)





# 1.2.0 (2020-12-01)


### chore

* translate new presets
* update dependencies (CU-3cj43t)
* update major dependencies (CU-3cj43t)
* update to composer v2 (CU-4akvjg)
* update to core-js@3 (CU-3cj43t)
* update to TypeScript 4.1 (CU-3cj43t)


### feat

* new cookie preset Zoho Forms and Zoho Bookings (CU-awy9wa)


### refactor

* enforce explicit-member-accessibility (CU-a6w5bv)





## 1.1.3 (2020-11-26)


### fix

* compatibility with WebFontLoader for Google Fonts and Adobe Typekit (CU-aq01tu)
* never block codeOnPageLoad scripts of cookies (introduce consent-skip-blocker HTML attribute, CU-aq01tu)





## 1.1.2 (2020-11-25)


### fix

* code on page load should be execute inside head-tag (CU-aq01tu)
* consent does not get saved in development websites (CU-aq0tbk)
* wrong link to consent forwarding in german WordPress installation





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
