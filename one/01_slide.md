!SLIDE 

# A CLI Environment for Client-Side Development #

* Derek Kastner - @dkastner

!SLIDE

# I hate the mouse #

* I prefer command-line tests, vim

!SLIDE

# Jasmine in the Browser

* Wasn''t doing it for me

!SLIDE

# I Love Testing Node.js Code #

* Fast
* Great frameworks (Vows.js, Sinon.js)

!SLIDE

# I Love Node.js Modules & npm #

* Organized
* Rich ecosystem, e.g.
  * JSONPath
  * REST clients
  * URI parsing

!SLIDE

# Node.js => Browser #

!SLIDE

# Every Month, a New Packager/Concatenator

* ender
* bpm
* jammit
* sprockets
* many more...

!SLIDE

# Browserify #

* Everything and a bag of chips
* Node.js core compatibility layer

!SLIDE

# Development Process #

* Install npm modules
  * Use package.json
  * npm install

!SLIDE

# Development Process #
* Write tests
  * [Organized into modules](https://github.com/dkastner/CM1.js/blob/master/test/adapters/websocket-adapter-test.js)

!SLIDE

# Development Process #

* Write code
  * [Organized into modules](https://github.com/dkastner/CM1.js/blob/master/lib/adapters/websocket-adapter.js)

!SLIDE

# Development Process #

* Run CLI tests
* At end of feature, run in-browser tests
  * Cucumber/Capybara-webkit

!SLIDE

# Development Process #

* Export for the web
  * browserify tool
  * [nodeify](http://github.com/dkastner/nodeify) - Browserify for Rails

!SLIDE

# Other Benefits #

* Break out project into npm packages
* Simpler CI setup

!SLIDE

# Real Examples #

* [http://github.com/brighterplanet/careplane](http://github.com/brighterplanet/careplane)
* [http://github.com/dkastner/CM1.js](http://github.com/dkastner/CM1.js)
