[![Build Status](https://travis-ci.org/jhipster/generator-jhipster.svg?branch=master)](https://travis-ci.org/jhipster/generator-jhipster)

Full documentation and information is available on our website at [http://jhipster.github.io/](http://jhipster.github.io/)

[Sync a fork](https://help.github.com/articles/syncing-a-fork)

Grunt and Grunt plugins are installed and managed via [npm](https://npmjs.org/), the [Node.js](http://nodejs.org/) package manager. 

####[package.json](https://www.npmjs.org/doc/files/package.json.html)
This file is used by [npm](https://npmjs.org/) to store metadata for projects published as npm modules. You will list grunt and the Grunt plugins your project needs as [devDependencies](https://www.npmjs.org/doc/files/package.json.html#devdependencies) in this file.

The `package.json` file belongs in the root directory of your project, next to the `Gruntfile`, and should be committed with your project source. Running `npm install` in the same folder as a `package.json` file will install the correct version of each dependency listed therein.

####Gruntfile
This file is named `Gruntfile.js` or `Gruntfile.coffee` and is used to configure or define tasks and load Grunt plugins.
The `Gruntfile.js` or `Gruntfile.coffee` file is a valid JavaScript or CoffeeScript file that belongs in the root directory of your project, next to the `package.json` file, and should be committed with your project source.

A `Gruntfile is` comprised of the following parts:

1. The "wrapper" function
2. Project and task configuration
3. Loading Grunt plugins and tasks
4. Custom tasks

Read more [here](http://gruntjs.com/getting-started)

####[JSHint](http://www.jshint.com/about/)
JSHint is a community-driven tool to detect errors and potential problems in JavaScript code and to enforce your team's coding conventions. It is very flexible so you can easily adjust it to your particular coding guidelines and the environment you expect your code to execute in. 

####[load-grunt-tasks](https://github.com/sindresorhus/load-grunt-tasks)
`require('load-grunt-tasks')(grunt);`
Load multiple grunt tasks using globbing patterns
Usually you would have to load each task one by one, which is unnecessarily cumbersome.
This module will read the `dependencies`/`devDependencies`/`peerDependencies` in your `package.json` and load grunt tasks that match the provided patterns.

For those new to Bower, it’s an unopinionated, generic package manager for the web platform that aims to help with front-end package management. Bower works over git, its packages can be made up of any type of asset HTML/CSS/JS and use any type of transport (CJS/AMD/ES6 modules). It’s currently used by Bootstrap, Normalize, AngularJS and many other open-source projects.

We have a plethora of tools, frameworks, languages, abstractions and platforms!
