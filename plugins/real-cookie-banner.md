# real-cookie-banner

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.12.0 (2021-03-10)


### build

* plugin tested for WordPress 5.7 (CU-f4ydk2)


### chore

* register and translate new presets (CU-eyzegt, CU-f4yzpm)


### feat

* new cookie and content blocker preset Yandex Metrica (CU-f4yzpm)
* new cookie preset for Bing Ads (Microsoft UET) (CU-eyzegt)
* new cookie preset found.ee (CU-f97ady)


### fix

* more granular translation for TranslatePress for blockers, cookie group, cookies and banner texts





# 1.11.0 (2021-03-10)


### chore

* hide some notices on try.devowl.io (CU-f53trz)


### feat

* added ability to auto play videos if they got unblocked (Divi Page Builder, CU-f51p51)
* added ability to auto play videos if they got unblocked (JetElements for Elementor, CU-f51p51)
* autoplay YoutTube and Vimeo videos after unblocking through content blocker (CU-f558r1)


### fix

* compatibility with Combine JavaScript in WP Rocket (CU-f35k4j)
* compatibility with Divi videos (e.g. YouTube) when using an overlay
* compatibility with JetElements for Elementor Video Player (CU-f51p51)
* compatibility with lazy loaded scripts e.g. WP Rocket when they are present in the configuration list (CU-f35k4j)
* in some cases the blocked content was still display:none after unblocking (e.g. GTranslate, CU-f35k4j)





# 1.10.0 (2021-03-02)


### chore

* update german text for privacy settings history dialog title (CU-ev2070)


### feat

* allow to customize more texts for content blocker (CU-ev2070)
* new cookie preset (CU-ev6jyb)


### fix

* allow HTML formatting in content blocker accept info text (CU-ev2070)
* compatibility with Thrive Architect embeds
* compatibility with Thrive Archtitect Custom HTML block
* do not allow cookie duration greater than 365 (CU-cpyc46)
* do not override position:relative for content blocker





# 1.9.0 (2021-02-24)


### chore

* drop moment bundle where not needed (CU-e94pnh)
* introduce new JavaScript API window.consentApi.consentSync


### docs

* rename test drive to sanbox (#ef26y8)


### feat

* new cookie banner preset 'Ronny's Dialog'
* new customizer option in Body > Accept all Button > Align side by side (CU-cv0d8g)


### fix

* compatibility with X Theme and Cornerstone
* content blocker containers may also have an empty style
* content blocker for JetPack Site Stats too aggressive when using together with wordpress.com
* content blocking for Quform in some cases to aggressive (#ejxq3b)
* do not annonymously server when SCRIPT_DEBUG is active
* do not apply style to parent containers if no style was previously present
* do not show cookie banner when editing in Divi and Beaver Builder page builder
* illegal mix of collations (CU-ef1dtp)
* in some cases the original iframe was blocked, but not completely hidden
* when a profile deactivate syntax highlighting, the cookie form did not work (CU-en3mxa)





# 1.8.0 (2021-02-16)


### chore

* register and translate new cookie and content blocker presets
* show notice for Quform cause content blocker is not necessery (CU-cawja6)


### feat

* allow to apply content blockers to JSON output of e.g. REST services
* improve English translation (#devznm)
* new cookie and content blocker preset Issuu (CU-e14yht)
* new cookie and content blocker preset Pinterest Tag (CU-eb3wu9)
* new cookie and content blocker preset Quform (CU-cawja6)
* new cookie preset Klarna Checkout for WooCommerce (CU-e2z7u7)
* new cookie preset TranslatePress (CU-e14nf6)


### fix

* compatibility Instagram blocker with WoodMart theme
* compatibility with Elementor inline styles
* compatibility with TranslatePress (CU-cew7v9)
* do not block links without class and external URLs
* do not output calculated time for blocker when not requested; compatibility with Themebeez Toolkit
* show correct tooltip when Google / Matomo Tag Manager template can not be created (CU-e6xyc5)





## 1.7.3 (2021-02-05)


### docs

* update README to be compatible with Requires at least (CU-df2wb4)


### fix

* in some edge cases the wordpress autoupdater does not fire the wp action and dynamic javascript assets are not generated





## 1.7.2 (2021-02-05)


### chore

* show notice after one week when setup not yet completed (CU-djx8ga)


### fix

* deliver anonymous assets like JavaScripts files correctly (CU-dgz2p9)
* remove anonymous javascript files on uninstall (CU-dgz2p9)





## 1.7.1 (2021-02-02)

**Note:** Version bump only for package @devowl-wp/real-cookie-banner





# 1.7.0 (2021-02-02)


### chore

* allow to edit custom post types and taxnomies to be edited via native UI for debug purposes
* remove limit for cookies and content blockers (CU-d6z2u6)


### docs

* improved product description for wordpress.org (#d6z2u6)


### feat

* new cookie and content blocker preset MailerLite (CU-d10rw9)
* new cookie preset CleanTalk Spam Protection (CU-d93t70)
* new cookie preset WordFence (CU-dcyv72)


### fix

* allow to block inline styles by URL (CU-d10rw9)
* compatibility with Custom Facebook Feed Pro v3.18 (CU-cwx3bn)
* compatibility with FooBox lightbox (CU-dczh1k)
* compatibility with TranslatePress to avoid flickering (CU-dd4a3q)
* compatibility with Uncode Google Maps block (CU-d12m5q)
* content blocker should also execute window 'load' event after unblock (CU-d12m5q)
* do correctly find duplicate content blockers and avoid them (CU-d10rw9)
* do not block twice for custom element blockers (CU-d10rw9)
* translated page in footer is not shown in PolyLang correctly (CU-d6wumw)





# 1.6.0 (2021-01-24)


### chore

* register new cookie and content blockers and update README (CU-cwx3bn)


### feat

* allow to make customizer fields resettable with a button (CU-crwyqn)
* new banner preset in customizer 'Clean Dialog'
* new content blocker preset CleverReach with Google Recaptcha (CU-cryuv0)
* new cookie and content blocker preset Custom Twitter Feeds (Tweets Widget) (CU-cwx3bn)
* new cookie and content blocker preset Feeds for YouTube (CU-cwx3bn)
* new cookie and content blocker preset FontAwesome (CU-cx067u)
* new cookie and content blocker preset Smash Balloon Social Post Feed (CU-cwx3bn)
* preset extends middleware now supports extendsStart and extendsEnd for array properties (CU-cwx3bn)


### fix

* allow all URLs for affiliates in PRO version (CU-cyyh2z)
* compatibility with CloudFlare caches; nonce is no longer needed as we have rate limit in public APIs (CU-cwvke2)
* compatibility with Impreza lazy loading grid (CU-94w719)
* improve UX when creating Content Blocker and open the Add-Cookie form in a modal instead of new tab (CU-cz12vj)
* review 1 (CU-cz12vj)
* wrong character encoding for VG Wort preset


### refactor

* remove unused classes and methods


### revert

* always show recommened cookies in content blocker select (CU-cwx3bn)


### style

* do not break line in cookie preset selector description
* use flexbox instead of usual containers for banner buttons (CU-cv0ff2)





# 1.5.0 (2021-01-18)


### chore

* introduce new developer filters RCB/Blocker/KeepAttributes and RCB/Blocker/VisualParent (CU-cn0wvd)
* new Consent API function consentApi.consent() and consentApi.consentAll() to wait for consent
* presets can no be extended by a parent class definition
* register new cookie and content blockers and update README (CU-cewwda)
* translate new presets, update README


### feat

* new content blocker preset Google Analytics (CU-cewwda)
* new cookie and content blocker preset Analytify (CU-cewwda)
* new cookie and content blocker preset ExactMetrics (CU-cewwda)
* new cookie and content blocker preset Facebook For WooCommerce (CU-cewwda)
* new cookie and content blocker preset GA Google Analytics (CU-cewwda)
* new cookie and content blocker preset Mailchimp for WooCommerce (CU-cn234z)
* new cookie and content blocker preset Matomo WordPress plugin (CU-ch3etd)
* new cookie and content blocker preset MonsterInsights (CU-cewwda)
* new cookie and content blocker preset WooCommerce Google Analytics Integration (CU-cewwda)
* new cookie preset Lucky Orange (CU-ccwj8v)
* new cookie preset WooCommerce Stripe (CU-cn232u)
* recommend MonsterInsights content blocker in Google Analytics cookie preset (CU-cewwda)


### fix

* automatically invalidate preset cache after any plugin activated / deactivated
* compatibility with FloThemes embed codes and blocks (CU-cn0wvd)
* do not show footer links when label is empty (CU-cjwyqw)
* do not show hidden or disabled content blocker presets in cookie form
* extended presets can disable technical handling through compatible plugin (CU-cewwda)
* footer not shown when imprint empty in PRO version
* include description in preset search index
* overcompressed logo
* review 1 (CU-cewwda)


### refactor

* presets gets more and more complex, let's simplify with a middleware system


### style

* gray out disabled cookie and content blocker presets
* gray out plugin-specific cookie and content blocker presets
* show a tooltip when a preset is currently disabled





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
