Relisten
========
Downloads the playlists of all radiostations between two certain dates from [https://relisten.be](https://relisten.be) and writes them to a CSV-file.

Installation
------------
1. Install NodeJS. See [http://nodejs.org](http://nodejs.org) for instructions.
1. Install the [Gulp](http://gulpjs.com) build system:
`
    $ npm install -g gulp
`
1. Install the NodeJS dependencies:
`
    $ npm install
`
1. Build the project
`
    $ gulp install
`

Usage
-----
Browser version:

    $ open dist/index.html

NodeJS version:

    $ npm start

Information
-----------
### Browser version
The browser version is packaged using [Browserify](http://browserify.org). Here the dates can be chosen using a simple date picker.

This version however has some XSS issues.

### NodeJS version
In the NodeJS version, the start and end dates are hard-coded. See `app/js/nodeApp.js` for information and customization.
