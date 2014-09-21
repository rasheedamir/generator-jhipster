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
The static code analysis and code quality tools such as JSHint help reduce the number of syntax errors and improve the quality of the code.

####[load-grunt-tasks](https://github.com/sindresorhus/load-grunt-tasks)
`require('load-grunt-tasks')(grunt);`
Load multiple grunt tasks using globbing patterns
Usually you would have to load each task one by one, which is unnecessarily cumbersome.
This module will read the `dependencies`/`devDependencies`/`peerDependencies` in your `package.json` and load grunt tasks that match the provided patterns.

For those new to Bower, it’s an unopinionated, generic package manager for the web platform that aims to help with front-end package management. Bower works over git, its packages can be made up of any type of asset HTML/CSS/JS and use any type of transport (CJS/AMD/ES6 modules). It’s currently used by Bootstrap, Normalize, AngularJS and many other open-source projects.

We have a plethora of tools, frameworks, languages, abstractions and platforms!

####[PhantomJS](http://phantomjs.org/) 

[PhantomJS](http://phantomjs.org/) is a headless WebKit-based rendering engine and interpreter with a JavaScript API. Think of PhantomJS as a browser that doesn’t have any graphical user interface. PhantomJS can execute HTML, CSS, and JavaScript code. Because PhantomJS is not required to render a browser’s GUI, it can be used in display-less environments (for example, a CI server) to run tests. 
In our case, Grunt automatically spawns the PhantomJS instance, executes the code of our tests, reads the execution results using the PhantomJS API, and prints them out in the console. 

[HTML5 Boilerplate](http://html5boilerplate.com/)
When you start a new project, it's unlikely you start with a blank HTML file. You probably have some kind of starting template, or your IDE builds a rough file with some elements preloaded. That's what HTML5 Boilerplate is: a starter template to use on all your projects.
HTML5 Boilerplate is a professional front-end template for building web applications or sites. It's chock-full of cross-browser compatibility features, CSS resets, base styles, and optional server configs to give your project the best possible start.
