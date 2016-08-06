#AngularJS Modular Demo
Demonstrates Angular modularity, testing, Gulp task automation, and more.

>*Opinionated AngularJS style guide for teams by [@john_papa](//twitter.com/john_papa)*

>More details about the styles and patterns used in this app can be found in my [AngularJS Style Guide](https://github.com/johnpapa/angularjs-styleguide) and my **AngularJS Patterns: Clean Code**(coming soon) course at [Pluralsight](http://pluralsight.com/training/Authors/Details/john-papa) and working in teams. 

## Structure
	/build 	(created on the fly)
	/gulp	
	/src
		/client
			/app
			/content
			/test
		/server
			/data
			/routes
	
## Requirements

- Install Node
	- on OSX install [home brew](http://brew.sh/) and type `brew install node`
	- on Windows install [chocolatey](https://chocolatey.org/) and type `choco install nodejs`
- On OSX you can alleviate the need to run as sudo by [following these instructions](https://github.com/sindresorhus/guides/blob/master/npm-global-without-sudo.md). I highly recommend this step on OSX
- Open terminal
- Type `npm install -g node-inspector bower gulp`

## Installing Node.js and Bower Packages
- Open terminal
- Type `npm install`

## Installing Bower Packages
`npm install` will install these too, but you can do it manually.
- Open terminal
- Type `bower install`

## Running
Runs locally, no database required.
- Type `gulp serve-dev`
