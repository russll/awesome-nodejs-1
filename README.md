# Awesome Node.js
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/onerussell/awesome-nodejs-1?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A curated list of astonishing Node.js frameworks, libraries and resources. Inspired by [awesome-php](https://github.com/ziadoz/awesome-php) and [awesome-python](https://github.com/vinta/awesome-python).

Your pull requests are very welcome! Let's make this the awesomest resource for Node!

- [Awesome Node.js](#awesome-nodejs)
    - [Environment Management](#environment-management)
    - [Integrated Development Environments](#integrated-development-environments)
    - [Documentation](#documentation)
    - [Package Management](#package-management)
    - [Build Tools](#build-tools)
    - [Communication](#communication)
    - [Database Drivers](#database-drivers)
    - [Debugging Tools](#debugging-tools)
    - [Logging](#logging)
    - [ORM](#orm)
    - [Web Frameworks](#web-frameworks)
    - [Application Servers](#application-servers)
    - [Content Management System](#content-management-system)
    - [RESTful API](#restful-api)
    - [Forms](#forms)
    - [Files and MIME Type Manipulation](#files-and-mime-type-manipulation)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Template Engine](#template-engine)
    - [Tools for building CLIs](#tools-for-building-clis)
    - [Async Control Flow](#async-control-flow)
    - [Rate Limiting](#rate-limiting)
    - [Testing](#testing)
    - [Miscellaneous](#miscellaneous)
- [Other Awesome Lists](#other-awesome-lists)

## Environment Management

*Libraries for Node version and environment management.*

* [nodeenv](https://github.com/ekalinin/nodeenv) - Virtual environment for Node.js & integrator with virtualenv.
* [nave](https://github.com/isaacs/nave) - Virtual Environments for Node.
* [n](https://github.com/visionmedia/n) - Node version management.
* [nvm](https://github.com/creationix/nvm) - Node Version Manager (does not require prior installation of node).

## Integrated Development Environments

*IDEs and Editors for development*

* [Enide](http://www.nodeclipse.org/enide/) - Node Eclipse IDE with Nodeclipse plugin.
* [InteliJIDEA](http://www.jetbrains.com/idea/features/nodejs.html) - Fast Node plugin for InteliJ.
* [Webstorm](http://www.jetbrains.com/webstorm/features/#node.js) - "Create great websites and applications in a great IDE. The best JavaScript IDE and HTML editor is at your service."
* [Visual Studio](http://www.visualstudio.com/) - With [Node.js Tools for Visual Studio](https://nodejstools.codeplex.com/) (Supports editing, IntelliSense, profiling, npm, TypeScript, debugging locally and remotely on Windows/MacOS/Linux)
* [Atom](https://github.com/atom/atom) - The hackable editor by GitHub
* [Brackets](https://github.com/adobe/brackets) - An open source code editor for the web, written in JavaScript, HTML and CSS.
* [Cloud9](https://c9.io/site/code-smarter-code-together/) - Web editor with collaboration tools.
* [Notepad++](http://notepad-plus-plus.org) - Notepad++ is a free source code editor and Notepad replacement that supports several languages.
* [CmdEr](https://github.com/bliker/cmder) - Not really and IDE, but a great "lovely console emulator package for Windows"
* [Cloud Commander](http://cloudcmd.io) - Web file manager. Has editor and console. Allows you to develop web applications, sites etc.

## Documentation

*Libraries for generating project documentation.*

* [Docco](http://jashkenas.github.io/docco/) - Docco is a quick-and-dirty documentation generator, written in Literate CoffeeScript.
* [Groc](https://github.com/nevir/groc) - Documentation generation, in the spirit of literate programming.
* [dox](https://github.com/visionmedia/dox) - JavaScript documentation generator for node using markdown and jsdoc.

## Package Management

*Libraries for package and dependency management.*

* [npm](https://www.npmjs.org/) - Default package manager. Installs, publishes and manages node programs.

## Build Tools

*Libraries for building and task running*

* [Gulp.js](http://gulpjs.com/) - A streaming build system which use of streams and code-over-configuration.
* [Grunt.js](http://gruntjs.com/) - A task runner to ease epetitive tasks like unit testing, compilation and so on.
* [Nodemon](http://nodemon.io/) - A dev utility that monitor any changes in source and automatically restart server.
* [Browserify](http://browserify.org/) - Browserify lets you require('modules') in the browser by bundling up all of your dependencies.

## Communication

* [Socket.IO](http://socket.io/) - Websocket framework for Node and Javascript.
* [SockJS](https://github.com/sockjs) - Websocket emulation.
* [Primus](https://github.com/primus/primus) - An abstraction layer for real-time frameworks to prevent module lock-in.
* [BinaryJS](http://binaryjs.com/) - BinaryJS is bidrectional realtime binary data with binary websockets

## Database Drivers

*Libraries for connecting and operating databases*

* [Node-mysql](https://github.com/felixge/node-mysql/) - A pure node.js JavaScript Client implementing the MySql protocol.
* [Node-mongodb-native](https://github.com/mongodb/node-mongodb-native/) - Mongo DB Native NodeJS Driver.
* [Node-redis](https://github.com/mranney/node_redis) - Redis Driver, use [hideredis](https://github.com/redis/hiredis-node) for native parser, and checkout [then-redis](https://github.com/mjackson/then-redis) for a Promise-based API.

## Debugging Tools

*Tools for debugging Node applications*

* [node-inspector](https://github.com/node-inspector/node-inspector) - Node.js debugger based on Blink Developer Tools.
* [longjohn](https://github.com/mattinsler/longjohn) - Longer stack traces for Node.
* [TypesJs](https://github.com/ChrisAntaki/typesjs) - Easy type checking, for Node & browsers.
* [Nodev](https://github.com/akamensky/nodev) - Tool for easier debugging based on nodemon and node-inspector.
* [cf-node-debug](https://www.npmjs.org/package/cf-node-debug) - Proxy to aid in debugging node running on a PaaS.

## Logging

*Tools for generating and working with log files.*

* [caterpillar](https://github.com/bevry/caterpillar) - A logging system that can log and pipe the output off to different locations.
* [tracer](https://github.com/baryon/tracer) - A powerful and customizable logging library for node.js.
* [Log.io](http://logio.org/) - Real time logging facility on the browser.
* [Bunyan](https://github.com/trentm/node-bunyan) - A simple and fast JSON logging module for node.js services.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [Sequelize](http://sequelizejs.com/) - Sequelize library provides easy access to MySQL, MariaDB, SQLite or PostgreSQL databases.
* [Node-orm2](https://github.com/dresende/node-orm2) - Another Relational Object Mapper.
* [Mongoose](http://mongoosejs.com/) - Almost an ORM for mongodb.

## Web Frameworks

*Web development frameworks.*

* [Express](http://expressjs.com/) -  A minimal and flexible node.js web application framework.
* [Flatiron](http://flatironjs.org/) - An adaptable framework for building modern web applications.
* [Koa](http://koajs.com/) - A framework which aims to be a smaller, more expressive, and more robust foundation for web applications.
* [Totaljs](http://www.totaljs.com/) - Friendly responsive design web application framework for node.
* [Meteor](https://www.meteor.com/) - A platform that has strong features such as live page update, sync and hopt code pushes.
* [Hapi](https://github.com/spumko/hapi) - A rich framework for building applications and services.
* [Derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * [Derby-awesome](https://github.com/onerussell/awesome-derby) - A collection of awesome derby components

## Application Servers

*Application Server is an environment to run and manage multiple applications.*

* [Impress](https://github.com/tshemsedinov/impress) - Impressive multipurpose scalable Application Server optimized for high load API and web applications.

## Content Management System

* [Calipso](http://calip.so/) - Calipso is a simple CMS, built along similar themes to Drupal and Wordpress.
* [KeystoneJS](http://keystonejs.com/) - Node.js CMS and web application platform built on Express and MongoDB.

## RESTful API

*Libraries for developing RESTful APIs.*

* [Sails](http://sailsjs.org) - MVC framework which generates a RESTful JSON API.
* [Node-restify](http://mcavage.me/node-restify/) - A node.js module built specifically to build correct REST web services.
* [Heimdall](https://github.com/binarymax/heimdall) - REST API Guardian for Express.

## Forms

*Libraries for deal with forms and form data*

* [node-validator](https://github.com/chriso/validator.js) - A simple string validation and sanitization
* [express-validator](https://github.com/ctavan/express-validator) - An express.js middleware for node-validator.

## Files and MIME Type Manipulation

* [PDFKit](http://pdfkit.org/) - A JavaScript PDF generation library for Node and browser.

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [PassportJS](http://passportjs.org/) - Simple authentication middleware framework.
* [ldapjs](http://ldapjs.org/) - Pure JavaScript, from-scratch framework for implementing LDAP clients and servers.
* [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - OAuth 1.0a signature generator

## Template Engine

*Libraries and tools for templating and lexing.*

* [ECT](http://ectjs.com/) - "Fastest JavaScript template engine with embedded CoffeeScript syntax" as they say (benchmark proof).
* [Jade](http://jade-lang.com/) - Handful node template engine.
* [Swig](http://paularmstrong.github.io/swig/) - A simple, powerful, and extendable JavaScript Template Engine.

## Tools for building CLIs

*Libraries and tools which support you by building Command-Line Interfaces.*

* [Inquirer](https://github.com/SBoudrias/Inquirer.js) - A collection of common interactive command line user interfaces. *Ask questions, parsing, validating answers, managing hierarchical prompts and providing error feedback.*
* [commander.js](https://github.com/visionmedia/commander.js) - The complete solution for node.js command-line interfaces, inspired by Ruby's commander.
* [cli](https://github.com/chriso/cli) - Rapidly build command line apps with node.
* [cli-table](https://github.com/LearnBoost/cli-table) - Pretty unicode tables for the CLI with Node.JS
* [blessed](https://github.com/chjj/blessed) - A curses-like library for node.js.
* [chalk](https://github.com/sindresorhus/chalk) - Terminal string styling done right
* [minimist](https://github.com/substack/minimist) - Simple module for command line arguments parsing.
* [read](https://github.com/isaacs/read) - For reading user input from stdin.
* [colors.js](https://github.com/Marak/colors.js) - get colors in your node.js console like what.
* [configstore](https://github.com/yeoman/configstore) - Easily load and persist config without having to think about where and how.
* [blessed](https://github.com/chjj/blessed) - A curses-like library for node.js.
* [log-symbols](https://github.com/sindresorhus/log-symbols) - Colored symbols for various log levels.https://github.com/sindresorhus/log-symbols
* [terminal-menu](https://github.com/substack/terminal-menu) - retro ansi terminal menus for serious 80s technicolor business.
* [cli-spinner](https://github.com/helloIAmPau/node-spinner) - A simple spinner for node cli.
* [text-table](https://github.com/substack/text-table) - generate borderless text table strings suitable for printing to stdout.

## Async Control Flow

*Libraries that help you manage asyncronous control flow and avoid callback hell.*

* Callback-based:
    * [Async](https://github.com/caolan/async) - Utility module which provides straight-forward, powerful functions for working with asynchronous JavaScript.
* Promise-based ([Promises/A+](http://promises-aplus.github.io/promises-spec/)):
    * [Q](https://github.com/kriskowal/q) - Full-featured promise library with large API covering any situation you may encounter.
    * [RSVP.js](https://github.com/tildeio/rsvp.js) - Lightweight, but still compliant, promise library.
    * [when.js](https://github.com/cujojs/when) - Rock solid, battle tested promise library.
    * [Bluebird](https://github.com/petkaantonov/bluebird) - Bluebird is a fully featured promise library with focus on innovative features and performance.
* Fibers-base ([node-fibers](https://github.com/laverdet/node-fibers/)):
    * [asyncawait](https://github.com/yortus/asyncawait) - Inspired by C# async/await feature, implementation of the same patter using fibers.
* Generator-based:
    * [Co](https://github.com/visionmedia/co) - Generator based flow-control goodness for nodejs and the browser.

## Rate Limiting

*Libraries that help restrict the frequency of certain actions.*

* [Bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.

## Testing

*Testing frameworks.*

* [mocha](https://github.com/visionmedia/mocha) - Mocha is a feature-rich JavaScript test framework running on node.js and the browser, making asynchronous testing simple and fun.
* [tape](https://github.com/substack/tape) - tap-producing test harness for node and browsers.
* [should.js](https://github.com/visionmedia/should.js) - BDD style assertions for node.js -- test framework agnostic.
* [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [sinon](http://sinonjs.org/) - Standalone test spies, stubs and mocks for JavaScript.
* [Jasmine](http://jasmine.github.io/) - Simple Behavioral tests for Node and Javascript.
* [Expresso](http://visionmedia.github.io/expresso/) - TDD framework for Node.
* [NodeUnit](https://github.com/caolan/nodeunit) - Simple syntax unit test tool.
* [Concrete](http://ryankee.github.io/concrete/) - Continuous integration server.
* [ready.js](http://dsimard.github.io/ready.js/) - Continuous javascript integration tool.
* [Jezebel](https://github.com/benrady/jezebel) - A REPL and continuous test runner for Node.js Jasmine tests.

## Miscellaneous

*Miscellaneous Tools which doesn't fit to the other categories.*

* [Github Linker](https://chrome.google.com/webstore/detail/github-linker/jlmafbaeoofdegohdhinkhilhclaklkp) - Chrome extension that linkifies dependencies in package.json on GitHub.

# Other Awesome Lists
Other amazingly awesome lists can be found in the [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) projects.

# Contributing

Your contributions are always welcome!
