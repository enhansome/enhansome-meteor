# Awesome Meteor with stars

A curated list of awesome Meteor Packages, libraries and software.

The official Meteor resources page can be found [here](https://www.meteor.com/tools/resources)

* [Awesome Meteor](#awesome-meteor)
  * [Getting Started](#getting-started)
  * [Collections](#collections)
  * [Forms and Templates](#forms-and-templates)
  * [Users and Authentication](#users-and-authentication)
  * [REST](#rest)
  * [Files](#files)
  * [Routers](#routers)
  * [Debugging Tools](#debugging-tools)
  * [Editor Plugins](#editor-plugins)
  * [Search, sort and paginate](#search-sort-paginate)
  * [Mobile](#mobile)
  * [Offline](#offline)
  * [Testing](#testing)
  * [SEO](#seo)
  * [Data Visualization](#data-visualization)
  * [Analytics](#analytics)
  * [Cron Jobs](#cron-jobs)
  * [Administration](#administration)
  * [Performance](#performance)
  * [Monitoring](#monitoring)
  * [Deployment](#deployment)
    * [Docker Images](#docker-images)
  * [Front End Frameworks](#front-end-frameworks)
  * [Alternative Databases](#alternative-databases)
  * [Boilerplate](#boilerplate)
  * [Open Source Apps](#open-source-apps)
  * [Internationalization](#internationalization)
  * [Scaffolding](#scaffolding)
  * [Tooling](#tooling)
* [Resources](#resources)
  * [Books](#books)
  * [Courses](#courses)
    * [Free](#free)
    * [Paid](#paid)
  * [Tutorials](#tutorials)
  * [Blogs](#blogs)
  * [Websites](#websites)
  * [Q\&A](#q\&a)
  * [Community Newsletters](#community-newsletters)
  * [Social](#social)
  * [Work Opportunities](#work-opportunities)
  * [Related](#related)
* [Built With Meteor](#built-with-meteor)
* [Deprecated](#deprecated)
* [Contributing](#contributing)

***

## Getting Started

*Where to start*

* [Official Meteor tutorial](https://www.meteor.com/tutorials/react/creating-an-app)
* [Official Guide](http://guide.meteor.com/)

## Collections

*Helpers and expensions for collections*

* [aldeed:collection2](https://github.com/aldeed/meteor-collection2/) ⭐ 1,016 | 🐛 41 | 🌐 JavaScript | 📅 2026-08-17 - Automatic validation of insert and update operations on the client and server.
* [matb33:collection-hooks](https://github.com/Meteor-Community-Packages/meteor-collection-hooks) ⭐ 656 | 🐛 50 | 🌐 JavaScript | 📅 2026-08-17 - Extends Mongo.Collection with before/after hooks for insert/update/remove/find/findOne.
* [jagi:astronomy](https://github.com/jagi/meteor-astronomy/) ⭐ 604 | 🐛 47 | 🌐 JavaScript | 📅 2023-08-24 - The Model layer for Meteor.
* [simple-schema](https://github.com/aldeed/simple-schema-js) ⭐ 561 | 🐛 116 | 🌐 TypeScript | 📅 2026-08-20 - A JavaScript schema validation package that supports direct validation of MongoDB update modifier objects.
* [reywood:publish-composite](https://github.com/Meteor-Community-Packages/meteor-publish-composite) ⭐ 548 | 🐛 16 | 🌐 JavaScript | 📅 2026-01-21 - publish a set of related documents from various collections using a reactive join.
* [dburles:collection-helpers](https://github.com/dburles/meteor-collection-helpers/) ⭐ 495 | 🐛 12 | 🌐 JavaScript | 📅 2024-12-09 – Transform your collections with helpers that you define.
* [cultofcoders:grapher](https://github.com/cult-of-coders/grapher) ⭐ 276 | 🐛 67 | 🌐 JavaScript | 📅 2024-08-12 - Grapher: Meteor Collection Joins + Reactive GraphQL like queries.
* [sakulstra:aggregate](https://github.com/sakulstra/meteor-aggregate) ⭐ 39 | 🐛 4 | 🌐 JavaScript | 📅 2022-02-15 - Add proper aggregation support for Meteor.
* [quave:collections](https://github.com/quavedev/collections) ⚠️ Archived - Create collections in a standard way.

## REST

*REST support for Meteor*

* [maka:rest](https://atmospherejs.com/maka/rest) - automatically make your Meteor app accessible over HTTP and DDP alike.
* [vatfree:restivus](https://github.com/vatfree/meteor-restivus) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-17 - Make REST endpoints for your Meteor app with incredible ease.

## Forms and Templates

*Helpers for templates*

* [uniforms](https://github.com/vazco/uniforms) ⭐ 2,104 | 🐛 30 | 🌐 TypeScript | 📅 2026-01-12 - Bunch of React components and helpers to easily generate and validate forms. [Seamlessly integrate with `simpl-schema`](https://uniforms.tools/docs/installation).
* [aldeed:autoform](https://github.com/aldeed/meteor-autoform) ⭐ 1,428 | 🐛 24 | 🌐 JavaScript | 📅 2026-04-02 - UI components and helpers to easily create basic forms with automatic insert and update events, and automatic reactive validation.
* [aldeed:template-extension](https://github.com/aldeed/meteor-template-extension) ⭐ 219 | 🐛 5 | 🌐 JavaScript | 📅 2017-03-03 - A Meteor package: Replace already defined templates, inherit helpers and events from other templates.
* [ostrio:templatehelpers](https://github.com/VeliovGroup/Meteor-Template-helpers) ⭐ 34 | 🐛 0 | 🌐 JavaScript | 📅 2026-05-09 - Utility helpers for your Blaze templates.
* [kadira:blaze-layout](https://github.com/TeamGrid/blaze-layout) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-15 - Layout Manager for Blaze (works well with Meteor FlowRouter)

## Users and Authentication

*Tools for handling users and authentication*

* [accounts-js](https://github.com/accounts-js/accounts) ⭐ 1,502 | 🐛 63 | 🌐 TypeScript | 📅 2024-03-08 - A suite of packages aims to provide all the tools you need to build a flexible authentication and accounts management solution for your application.
* [alanning:roles](https://github.com/Meteor-Community-Packages/meteor-roles) ⭐ 913 | 🐛 46 | 🌐 JavaScript | 📅 2026-03-30 - Roles support for the built-in accounts packages.
* [meteor-user-status](https://github.com/Meteor-Community-Packages/meteor-user-status) ⭐ 556 | 🐛 41 | 🌐 JavaScript | 📅 2026-05-19 - Keeps track of users and their meta data.
* [accounts-ui](https://github.com/e-Potek/accounts-ui/) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2022-05-12 - Accounts UI for React in Meteor 1.3+.

## Administration

*Tools for administrating your Meteor apps*

* [yogiben:admin](https://github.com/yogiben/meteor-admin) ⭐ 822 | 🐛 171 | 🌐 CoffeeScript | 📅 2017-06-23 - A complete admin dashboard solution.
* [houston:admin](https://github.com/gterrono/houston) ⭐ 802 | 🐛 129 | 🌐 CoffeeScript | 📅 2017-05-16 - A zero-config, Django Admin-like admin for Meteor.
* [zodern:pure-admin](https://github.com/zodern/meteor-pure-admin) ⭐ 20 | 🐛 1 | 🌐 TypeScript | 📅 2023-08-31 - An isolated, customizable admin panel for Meteor.
* [Meteor Candy](https://www.meteorcandy.com/) - Fastest and easier way to add an admin panel to your app.

## Monitoring

*Tools for monitoring your Meteor apps*

* [monti-apm-agent](https://github.com/monti-apm/monti-apm-agent) ⭐ 48 | 🐛 15 | 🌐 JavaScript | 📅 2026-08-26 - Performance Monitoring for Meteor
* [lmachens:kadira](https://github.com/lmachens/kadira) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2019-11-25 - Performance Monitoring for Meteor
* [kschingiz:meteor-elastic-apm](https://github.com/kschingiz/meteor-elastic-apm) ⭐ 3 | 🐛 0 | 📅 2020-02-12 - Perfomance Monitoring for Meteor based on Elastic APM

## Performance

*Tools for speeding up your Meteor apps*

* [cultofcoders:redis-oplog](https://github.com/cult-of-coders/redis-oplog) ⭐ 389 | 🐛 71 | 🌐 JavaScript | 📅 2025-03-27 - Redis Oplog implementation to fully replace MongoDB Oplog in Meteor
* [staringatlights:fast-render](https://github.com/abecks/meteor-fast-render) ⭐ 58 | 🐛 9 | 🌐 JavaScript | 📅 2020-06-29 - An active fork of fast-render
* [maestroqadev:pub-sub-lite](https://github.com/adtribute/pub-sub-lite) ⚠️ Archived - Transform publications to be non-reactive.
* [epotek:method-cache](https://github.com/e-Potek/method-cache) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2023-12-15 - Meteor method caching using DataLoader
* [artillery-engine-meteor](https://github.com/kschingiz/artillery-engine-meteor) ⭐ 7 | 🐛 9 | 🌐 JavaScript | 📅 2023-03-02 - Artillery load testing for MeteorJS applications.

## Deployment

*Tools for deploying and maintaining Meteor apps*

* [meteor-up](https://github.com/zodern/meteor-up) ⭐ 1,267 | 🐛 226 | 🌐 JavaScript | 📅 2026-02-20 – Meteor Deployments.
* [demeteorizer](https://github.com/onmodulus/demeteorizer) ⭐ 701 | 🐛 15 | 🌐 JavaScript | 📅 2017-04-17 - Converts a Meteor app into a "standard" Node.js application
* [percolate:migrations](https://github.com/percolatestudio/meteor-migrations) ⭐ 243 | 🐛 17 | 🌐 JavaScript | 📅 2026-02-21 - Simple migration system for Meteor
* [pm2-meteor](https://github.com/andruschka/pm2-meteor) ⭐ 160 | 🐛 39 | 🌐 CoffeeScript | 📅 2022-04-28 - Simplest way to deploy, scale and run Meteor Apps with PM2.
* [mup-aws-beanstalk](https://github.com/zodern/mup-aws-beanstalk) ⭐ 124 | 🐛 45 | 🌐 JavaScript | 📅 2024-05-02 - Deploy Meteor apps to AWS Elastic Beanstalk using Meteor Up
* [meteor-azure](https://github.com/fractal-code/meteor-azure) ⭐ 66 | 🐛 5 | 🌐 JavaScript | 📅 2024-12-08 - Automate Meteor deployments on Azure App Service
* [meteor-kubernetes-guide](https://github.com/Gregivy/meteor-kubernetes-guide) ⭐ 41 | 🐛 2 | 📅 2019-05-06 - Deploy a Meteor app with Kubernetes.
* [meteor-hero](https://github.com/jkrup/meteor-hero) ⭐ 38 | 🐛 23 | 🌐 JavaScript | 📅 2023-01-04 - Deploy MeteorJS applications for free with one command utilizing Heroku's service.
* [meteor-google-cloud](https://github.com/EducationLink/meteor-google-cloud) ⭐ 29 | 🐛 21 | 🌐 JavaScript | 📅 2023-01-03 - Automate Meteor deployments on Google Cloud App Engine Flexible
* [waveshosting](https://github.com/nicolaslopezj/waveshosting) ⭐ 12 | 🐛 2 | 🌐 JavaScript | 📅 2022-01-10 - Web application to manage meteor deployments.
* [yamup](https://github.com/bordalix/yamup) ⭐ 10 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-21 - Deploy Meteor apps to your own Ubuntu server (EC2, ...) without dockers
* [meteorhacks:cluster](https://github.com/lmachens/cluster) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-07 - Clustering solution for Meteor with load balancing and service discovery

## Docker Images

* [meteor-base](https://github.com/disney/meteor-base) ⭐ 274 | 🐛 0 | 🌐 Shell | 📅 2026-08-26
* [docker-meteor](https://github.com/tozd/docker-meteor) ⭐ 54 | 🐛 0 | 🌐 Shell | 📅 2025-06-04
* [meteor-docker](https://github.com/zodern/meteor-docker) ⭐ 53 | 🐛 6 | 🌐 Shell | 📅 2026-08-14

## Routers

*Routers for Blaze*

* [iron:router](https://github.com/iron-meteor/iron-router) ⭐ 1,962 | 🐛 300 | 🌐 JavaScript | 📅 2017-11-11 - A router that works on the server and the browser, designed specifically for Meteor.
* [ostrio:flow-router-extra](https://github.com/VeliovGroup/flow-router) ⭐ 202 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-24 - Carefully extended `flow-router` package. Up-to-date version with support of latest Meteor's releases.
* [meteorhacks:picker](https://github.com/meteorhacks/picker) ⭐ 180 | 🐛 30 | 🌐 JavaScript | 📅 2018-03-21 - Server Side Router for Meteor.
* [msavin:parrot](https://github.com/msavin/Parrot) ⭐ 74 | 🐛 2 | 🌐 JavaScript | 📅 2018-02-28 - Web router specially designed for building SPAs using Meteor

## Offline

*Tools for Meteor offline support*

* [ground:db](https://github.com/GroundMeteor/db) ⭐ 569 | 🐛 66 | 🌐 JavaScript | 📅 2026-08-17 - GroundDB is a thin layer providing Meteor offline database and methods.
* [meteor-service-worker](https://github.com/NitroBAY/meteor-service-worker) ⭐ 138 | 🐛 2 | 🌐 JavaScript | 📅 2024-03-23 - Meteor specific service worker implementaion.
* [npdev:collections](https://github.com/CaptainN/npdev-collections) ⭐ 18 | 🐛 2 | 🌐 JavaScript | 📅 2020-12-14 - An easy way to create offline collections with SSR for Meteor
* [quave:pwa](https://github.com/quavedev/pwa) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2020-07-30 - A Meteor package that allows you to configure your PWA.

## Testing

*Testing tools*

* [meteortesting:mocha](https://github.com/meteortesting/meteor-mocha) ⭐ 66 | 🐛 37 | 🌐 JavaScript | 📅 2026-07-28 - Mocha test driver package for Meteor.
* [lmieulet:meteor-coverage](https://github.com/serut/meteor-coverage) ⚠️ Archived - Test coverage for Meteor.
* [antwaremx:meteorman](https://github.com/antwaremx/meteorman) ⭐ 53 | 🐛 1 | 🌐 Vue | 📅 2026-07-31 - Meteorman: A DDP Client with GUI to test Meteor methods and publications (like Postman).
* [hubroedu:mocha](https://github.com/hubroedu/meteor-mocha/) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2018-10-24 - Decaffed cultofcoders:mocha fork.

## SEO

*Search Engine Optimization tools*

* [ostrio:spiderable-middleware](https://github.com/VeliovGroup/spiderable-middleware/) ⭐ 43 | 🐛 5 | 🌐 JavaScript | 📅 2026-06-28 - Prerendering (*a.k.a. Spiderable*) with support of ES6 (ECMAScript2015) - Meteor app crawled perfectly by search engines.

## Files

*Handling files in Meteor*

* [ostrio:files](https://github.com/VeliovGroup/Meteor-Files) ⭐ 1,115 | 🐛 17 | 🌐 JavaScript | 📅 2026-07-27 - Upload files via DDP, HTTP and WebRTC/DC. To Meteor server FS, AWS, GridFS, DropBox or Google Drive. Fast, secure and robust.
* [netanelgilad:excel](https://github.com/netanelgilad/meteor-excel) ⚠️ Archived - Parsing and generating excel files (xlsx, xls).
* [@reactioncommerce/file-collections](https://github.com/reactioncommerce/reaction-file-collections) ⚠️ Archived - Reaction FileCollections is a set of NPM packages that provide the ability to support file uploads, storage, and downloads in Node and Meteor apps, and in browser JavaScript.
* [mikkelking:slingshot](https://github.com/Back2bikes/meteor-slingshot) ⭐ 13 | 🐛 6 | 🌐 JavaScript | 📅 2025-07-19 - Upload files directly to AWS S3, Google Cloud Storage and others in meteor.

## Search, sort and paginate

*Search, sort and paginate related tools*

* [matteodem:easy-search](https://github.com/matteodem/meteor-easy-search) ⭐ 428 | 🐛 33 | 🌐 JavaScript | 📅 2025-05-20 - Easy-to-use search with Blaze Components (+ Elastic Search Support)
* [alethes:pages](https://github.com/alethes/meteor-pages) ⭐ 399 | 🐛 75 | 🌐 CoffeeScript | 📅 2019-12-13 - Out of the box Meteor pagination.
* [tmeasday:publish-counts](https://github.com/percolatestudio/publish-counts) ⭐ 200 | 🐛 17 | 🌐 JavaScript | 📅 2024-03-20 - Publish the count of a cursor, in real time.
* [meteorhacks:search-source](https://github.com/meteorhacks/search-source) ⭐ 145 | 🐛 42 | 🌐 JavaScript | 📅 2020-10-01 - Reactive Data Source for Search.
* [percolate:find-from-publication](https://github.com/versolearning/find-from-publication) ⭐ 45 | 🐛 3 | 🌐 JavaScript | 📅 2019-05-28 - Enable finding all documents that have been published by a given publication.
* [meteor-publish-join](https://github.com/nlhuykhang/meteor-publish-join#readme) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2018-07-31 - A performant NPM package for publishing non-reactive or aggregated values.

## Mobile

*Mobile Development*

* [driftyco:ionic](https://github.com/driftyco/ionic) ⭐ 52,632 | 🐛 593 | 🌐 TypeScript | 📅 2026-08-27 - Official Ionic support for Meteor.
* [meteoric:ionic](https://github.com/meteoric/meteor-ionic) ⭐ 1,503 | 🐛 137 | 🌐 JavaScript | 📅 2022-08-15 - Ionic components for Meteor.
* [martijnwalraven:meteor-ios](https://github.com/martijnwalraven/meteor-ios) ⚠️ Archived - Integrates native iOS apps with the Meteor platform through DDP.
* [delight-im/Android-DDP](https://github.com/delight-im/Android-DDP) ⭐ 274 | 🐛 22 | 🌐 Java | 📅 2018-07-12 - DDP for clients on Android.
* [okland:accounts-phone](https://github.com/okland/accounts-phone) ⭐ 119 | 🐛 29 | 🌐 JavaScript | 📅 2016-08-31 - A login service based on mobile phone number for Meteor.
* [meteor-react-native](https://github.com/TheRealNate/meteor-react-native) ⭐ 67 | 🐛 7 | 🌐 JavaScript | 📅 2025-12-10 - Meteor client for React Native matching Meteor Spec.
* [meteor-push](https://github.com/activitree/meteor-push) ⭐ 28 | 🐛 10 | 🌐 JavaScript | 📅 2024-06-23 - Push notifications for cordova (ios, android) browser (Chrome, Safari, Firefox).
* [okland:camera-ui](https://github.com/okland/camera-ui) ⭐ 28 | 🐛 8 | 🌐 JavaScript | 📅 2017-09-25 - Meteor package for taking photos with user interface, one function call on desktop and mobile. Allows to choose between camera to photoLibrary on mobile.
* [percolatestudio/cordova-plugin-safe-reload](https://github.com/percolatestudio/cordova-plugin-safe-reload) ⭐ 14 | 🐛 2 | 🌐 JavaScript | 📅 2016-02-11 - Cordova plugin to watch and recover after a broken Meteor Hot Code Push.
* [quave:universal-links](https://github.com/quavedev/universal-links) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2020-08-14 - A Meteor package that allows you to expose your native iOS settings to enable Universal Links.

## Data Visualization

*Data Visualization in Meteor: charts, maps, tables, etc.*

* [aldeed:tabular](https://github.com/aldeed/meteor-tabular) ⭐ 360 | 🐛 113 | 🌐 JavaScript | 📅 2026-03-25 - Reactive datatables for large or small datasets.
* [aslagle:reactive-table](https://github.com/aslagle/reactive-table/) ⭐ 327 | 🐛 216 | 🌐 JavaScript | 📅 2024-01-30 - Reactive table for Meteor, using Blaze.
* [luixal:meteor-apexcharts](https://github.com/luixal/meteor-apexcharts) ⚠️ Archived - Reactive ApexCharts library packaged for Meteor.
* [luixal:blaze-paginated-custom-list](https://github.com/luixal/meteor-blaze-paginated-custom-list) ⚠️ Archived - Reactive and paginated item list.

## Analytics

*Analytics*

* [okgrow:analytics](https://github.com/okgrow/analytics/) ⭐ 214 | 🐛 18 | 🌐 JavaScript | 📅 2019-01-22 - Google Analytics, Mixpanel, KISSmetrics (and more) integration for meteor.
* [quave:analytics](https://github.com/quavedev/analytics) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2021-07-14 - A Meteor package that allows you to send your page views and more to Google Analytics.

## Cron Jobs

*Cron Jobs in Meteor*

* [percolate:synced-cron](https://github.com/percolatestudio/meteor-synced-cron) ⭐ 494 | 🐛 34 | 🌐 JavaScript | 📅 2024-01-18 - Cron system for Meteor. It supports syncronizing jobs between multiple processes.
* [msavin:sjobs](https://github.com/msavin/stevejobs/) ⭐ 210 | 🐛 10 | 🌐 JavaScript | 📅 2024-10-31 - A Meteor-first jobs queue / task scheduler.
* [ostrio:cron-jobs](https://github.com/VeliovGroup/Meteor-CRON-jobs) ⚠️ Archived - Package with similar API to native `setTimeout` and `setInterval` methods, but synced between all running Meteor (NodeJS) instances.

## Debugging Tools

*Debugging Tools*

* [msavin:mongol](https://github.com/msavin/Mongol/) ⭐ 817 | 🐛 4 | 🌐 JavaScript | 📅 2019-07-10 - Visual Editing Tool for Meteor for MongoDB Collections.
* [msavin:jetsetter](https://github.com/msavin/JetSetter) ⭐ 185 | 🐛 3 | 🌐 JavaScript | 📅 2015-07-07 - Visual Get/Set Tool for Meteor Session Variables.
* [meteor-devtools-evolved](https://github.com/leonardoventurini/meteor-devtools-evolved) ⭐ 177 | 🐛 29 | 🌐 TypeScript | 📅 2026-04-23 - A chrome extension.
* [babrahams:constellation](https://github.com/JackAdams/constellation-distro/) ⭐ 32 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-22 - An extensible dev console for Meteor.

## Editor Plugins

* [meteor-api](https://atom.io/packages/meteor-api) - Meteor addons for Atom.
* [meteor-zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Plugins#meteor) ⭐ 189,408 | 🐛 576 | 🌐 Shell | 📅 2026-08-25 - Completion for the meteor command.

## Scaffolding

*Scaffolding*

* [iron-cli](https://github.com/iron-meteor/iron-cli) ⭐ 637 | 🐛 25 | 🌐 JavaScript | 📅 2020-02-03 - A scaffolding command line tool for Meteor applications.
* [maka-cli](https://github.com/maka-io/maka-cli) ⭐ 0 | 🐛 0 | 📅 2026-08-27 - Maka-CLI is a command line tool, which organizes a web application's file structure and automates everyday package installation tasks for various application frameworks.
* [Meteor Kitchen](http://www.meteorkitchen.com/) - Code generator for Meteor.

## Tooling

* [ESLint-plugin-Meteor](https://github.com/dferber90/eslint-plugin-meteor/) ⚠️ Archived - ESLint plugin for Meteor.

## Boilerplate

* [matteodem - meteor-boilerplate](https://github.com/matteodem/meteor-boilerplate) ⭐ 818 | 🐛 10 | 🌐 JavaScript | 📅 2026-01-26
* [Pup](https://github.com/cleverbeagle/pup) ⭐ 551 | 🐛 12 | 🌐 JavaScript | 📅 2023-03-07
* [CaptainN - meteor-react-starter](https://github.com/CaptainN/meteor-react-starter) ⭐ 47 | 🐛 5 | 🌐 JavaScript | 📅 2023-01-07 - A starter project on Meteor with React.
* [React with Webpack + Meteor as a backend](http://julian.io/react-with-webpack-meteor-as-a-backend/)

## Open source apps

* [Wekan](https://github.com/wekan/wekan) ⭐ 21,066 | 🐛 282 | 🌐 JavaScript | 📅 2026-08-27 - Open source Trello-like kanban.
* [VulcanJS](https://github.com/VulcanJS/Vulcan) ⚠️ Archived - A toolkit to quickly build apps with React, GraphQL & Meteor.
* [Nosqlclient](https://github.com/nosqlclient/nosqlclient) ⭐ 3,469 | 🐛 19 | 🌐 JavaScript | 📅 2023-08-15 - MongoDB management tool.
* [coauthor](https://github.com/edemaine/coauthor) ⭐ 273 | 🐛 233 | 🌐 CoffeeScript | 📅 2026-07-22 - Coauthor supercollaboration/discussion forum.
* [Unchained Shop](https://github.com/unchainedshop/unchained) ⭐ 203 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-27 - Open source Commerce platform developed with Meteor.
* [radgrad2](https://github.com/radgrad/radgrad2) ⭐ 9 | 🐛 39 | 🌐 TypeScript | 📅 2023-03-04 - Meteor based education management system.
* [Rocket.Chat](https://rocket.chat/) - Realtime chat application built with Meteor.

## Internationalization

* [meteor-universe-i18n](https://github.com/vazco/meteor-universe-i18n) ⭐ 122 | 🐛 6 | 🌐 TypeScript | 📅 2026-01-08 - Internationalization package for React and Meteor.
* [meteor-accounts-t9n](https://github.com/softwarerero/meteor-accounts-t9n/) ⭐ 84 | 🐛 0 | 🌐 CoffeeScript | 📅 2025-09-10 - Translations for meteor account's error messages.
* [Meteor-Internationalization](https://github.com/veliovgroup/Meteor-Internationalization) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2023-04-05 - Super-Lightweight and fast i18n isomorphic driver for Meteor with support of placeholders.

## Front End Frameworks

*Alternative Front End Frameworks to Blaze*

* [Angular](https://github.com/Urigo/angular-meteor) ⭐ 2,335 | 🐛 25 | 🌐 Dockerfile | 📅 2023-05-02 - Working with Angular and Meteor.
* [Asteroid](https://github.com/mondora/asteroid) ⭐ 729 | 🐛 47 | 🌐 JavaScript | 📅 2017-08-01 - An alternative client for a Meteor backend.
* [Famo.us](https://github.com/gadicc/meteor-famous-views/) ⭐ 329 | 🐛 51 | 🌐 JavaScript | 📅 2016-07-27 - Famo.us and Meteor.
* [Angular 2](https://github.com/Urigo/angular2-meteor) ⭐ 297 | 🐛 5 | 📅 2017-10-16 - Working with Angular 2 and Meteor.
* [frozeman:build-client](https://github.com/frozeman/meteor-build-client) ⭐ 277 | 🐛 3 | 🌐 JavaScript | 📅 2026-03-03 - A tool to bundle the client part of a Meteor app.
* [ddp.js](https://github.com/mondora/ddp.js) ⭐ 210 | 🐛 13 | 🌐 JavaScript | 📅 2018-03-17 - Isomorphic JavaScript DDP client.
* [Svelte](https://github.com/zodern/melte) ⭐ 33 | 🐛 14 | 🌐 JavaScript | 📅 2025-03-19 - Build cybernetically enhanced web apps with Meteor and Svelte.
* [elm](https://github.com/ni-ko-o-kin/meteor-elm-example) ⭐ 4 | 🐛 9 | 🌐 Elm | 📅 2022-12-11 - elm as the view layer for a meteor based project.
* [React](http://react-in-meteor.readthedocs.org/en/latest/) - Working with React and Meteor.
* [Vue](https://github.com/meteor-vue) - Working with Vue and Meteor (plus single-file components & apollo support).

## Alternative Databases

*Alternative Databases for MongoDB*

* [simple:rethink](https://github.com/Slava/meteor-rethinkdb) ⭐ 302 | 🐛 12 | 🌐 JavaScript | 📅 2016-07-02 - RethinkDB integration for Meteor
* [numtel:pg](https://github.com/numtel/meteor-pg) ⭐ 299 | 🐛 8 | 🌐 JavaScript | 📅 2015-08-12 - Reactive PostgreSQL for Meteor
* [ostrio:neo4jdriver](https://github.com/VeliovGroup/ostrio-neo4jdriver/) ⭐ 52 | 🐛 0 | 🌐 CoffeeScript | 📅 2017-02-10 - Neo4j Driver for Meteor, with support of GrapheneDB
* [vlasky:mysql](https://github.com/vlasky/meteor-mysql) ⭐ 39 | 🐛 1 | 🌐 JavaScript | 📅 2026-02-18 - Reactive MySQL for Meteor
* [meteor-pg](https://github.com/Richie765/meteor-pg) ⭐ 25 | 🐛 1 | 🌐 JavaScript | 📅 2017-06-29 - New and improved PostgreSQL support for Meteor

# Resources

*Where to discover new Meteor things*

## Books

* [Meteor Cookbook](https://github.com/awatson1978/meteor-cookbook) ⭐ 1,665 | 🐛 31 | 🌐 Shell | 📅 2022-01-04
* [Meteor Explained](https://gumroad.com/l/meteor-explained)
* [Secure Meteor](https://www.securemeteor.com/)
* [meteor-tuts](https://www.meteor-tuts.com/) - Free
* [Meteor Tips](http://meteortips.com/) - Free
* [Pro Meteor](https://pdfslide.net/documents/pro-meteor-book.html) - Free

## Courses

* #### Free

  * [How to Create an App](https://www.youtube.com/c/Howtocreateanappdev/videos) - Most updated.
  * [EventedMind](https://learn-meteor.netlify.app/) - It's old but goes into detail regarding how Meteor internals.

* #### Paid
  * [Udemy - Learn React and Meteor in 2021: Build a multiplayer game](https://www.udemy.com/course/modern-web-development-with-react-and-meteor-2021/)
  * [Udemy - Realtime Applications with Meteor and Vue](https://www.udemy.com/course/meteor-vue) - Course in Spanish.
  * [leveluptutorials](https://www.leveluptutorials.com/) - Contains some free tutorials but mostly on 1.x.

## Tutorials

* [Phusion Passenger: Meteor tutorial](https://github.com/phusion/passenger/wiki/Phusion-Passenger:-Meteor-tutorial) ⭐ 5,088 | 🐛 234 | 🌐 C++ | 📅 2026-08-26
* [When a Meteor finally hits production](https://medium.com/@davidyahalomi/when-a-meteor-finally-hits-production-6c37b81f795b) - Blog post about deploying Meteor apps
* [Transform any Meteor App into a PWA](https://dev.to/jankapunkt/transform-any-meteor-app-into-a-pwa-4k44)

## Blogs

* [Official Meteor blog](http://blog.meteor.com)
* [The Meteor podcast](http://podcast.crater.io)

## Websites

* [Unofficial Meteor FAQ](https://github.com/oortcloud/unofficial-meteor-faq) ⭐ 947 | 🐛 20 | 📅 2019-10-04
* [Official website](https://www.meteor.com/)
* [Official Documentation](http://docs.meteor.com/)
* [Official Guide](http://guide.meteor.com/)
* [Atmosphere](https://atmospherejs.com/) - The catalog of Meteor packages, resources and tools.
* [Packosphere](https://packosphere.com/) - Alternative front-end for Meteor package system, built by [Kelly Copley
  ](https://github.com/copleykj)
* [Discover Meteor](https://book.discovermeteor.com/)
* [Meteorpedia](http://www.meteorpedia.com) ([infrequently](http://www.meteorpedia.com/special/RecentChanges/) updated)
* [Meetups](http://meteor.meetup.com/)
* [Reddit](https://www.reddit.com/r/meteor)
* [YouTube](https://www.youtube.com/channel/UC3fBiJrFFMhKlsWM46AsAYw) videos from meetups around the world
* [The Meteor Chef](https://themeteorchef.com)

### Q\&A

* [Stack Overflow](http://stackoverflow.com/questions/tagged/meteor?sort=newest\&pagesize=15)
* [Meteor forums](https://forums.meteor.com/)

### Community Newsletters

* [zodern](https://zodern.me/newsletter.html)
* [StorytellerCZ](https://forums.meteor.com/t/meteor-community-newsletter/50598)

## Social

* [Meteor Community Organization Slack Channel](https://github.com/Meteor-Community-Packages/organization#slack) ⭐ 40 | 🐛 7 | 📅 2022-12-09
* [Official Twitter Account](https://twitter.com/meteorjs)

## Work Opportunities

* [Awesome Meteor Jobs](https://github.com/harryadel/awesome-meteor-jobs) ⭐ 18 | 🐛 0 | 📅 2025-06-19
* [We work Meteor](https://www.weworkmeteor.com/)
* [Official Job Board](https://jobs.meteor.com/)

## Related

* [Awesome Blaze](https://github.com/arggh/awesome-blaze) ⭐ 29 | 🐛 3 | 📅 2019-12-07
* [Awesome Meteor Developers](https://github.com/harryadelb/awesome-meteor-developers) ⭐ 10 | 🐛 0 | 📅 2023-03-15

## Built With Meteor

*Commercial Grade Applications Built With Meteor*

* [Qualia](https://www.qualia.com/) - Real Estate Startup
* [Code Signal](https://codesignal.com/) - Skills-based assessment platform
* [Pathable](Pathable) - Events managment suite
* [MaestroQA](https://www.maestroqa.com/) - Quality assurance software

## Deprecated

*This section is desginated for resources which are no longer compatible with the current version of Meteor*

* [Meteor 1.4 + React For Everyone Tutorials](https://www.leveluptutorials.com/tutorials/meteor-1-4-react-for-everyone-tutorials)
* [Meteor 1.4 For Everyone](https://www.leveluptutorials.com/tutorials/meteor-1-4-for-everyone)
* [Intermediate Meteor](https://www.leveluptutorials.com/tutorials/intermediate-meteor)
* [Meteor For Everyone Tutorials](https://www.leveluptutorials.com/tutorials/meteor-for-everyone-tutorials)
* [tuts+ - Single Page Web Apps with Meteor](http://code.tutsplus.com/courses/single-page-web-apps-with-meteor)
* [Building a CMS-powered blog in Meteor](https://buttercms.com/blog/meteor-cms-blog-tutorial)
* [scotch.io - Building a Slack Clone in Meteor](https://scotch.io/tutorials/building-a-slack-clone-in-meteor-js-getting-started)

## [Contributing](https://github.com/urigo/awesome-meteor/blob/master/CONTRIBUTING.md) ⭐ 1,412 | 🐛 1 | 📅 2022-03-31

Your contributions are always welcome!

Thank you @gillesfabio for creating this repo!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
