Website Screenshot Generator
============================
This will generate and serve JPG screenshots of websites using PhantomJS, Node, 
and ImageMagick. Works pretty well on an Ubuntu 14.04 server. YMMV.

Requirements
------------
- [PhantomJS](http://phantomjs.org/)
- [ImageMagick](http://imagemagick.org/script/index.php)
- Recent version of [NodeJS](http://www.nodejs.org)

Installation
------------
- Clone this repository
- `npm install`

Usage
-------
- Run `node main.js`
- Go to http://localhost:9000/?url=URL_TO_SCREENSHOT

Make sure you use a full qualified URL (http:// and everything) in your request.

For example - http://localhost:9000/?url=http://www.github.com

Screenshots will be saved into the "screenshots" folder.

Screenshots are JPGs that are taken at 1280x900 and resized to 800x563
