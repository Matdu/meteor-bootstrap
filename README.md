# Meteor Bootstrap
Bootstrap for building Meteor App

https://github.com/atulmy/meteor-bootstrap

## Folder Structure

	meteor-bootstrap
	├── both
	│   ├── collections
	│   │   └── dairies.js
	│   │
	│   ├── schema
	│   │   └── dairies.js
	│   │
	│   ├── helpers.js
	│   ├── methods.js
	│   └── router.js
	│
	├── server
	│   ├── publish
	│   │   └── dairies.css
	│   │
	│   └── startup
	│       └── dairies.css
	│
	├── client
	│   ├── styles
	│   │   └── app.css
	│   │
	│   ├── subscribe
	│   │   └── dairies.js
	│   │
	│   ├── views
	│   │   ├── common
	│   │   │   ├── auth.html
	│   │   │   ├── loading.html
	│   │   │   └── common.js
	│   │	│
	│   │   ├── layout
	│   │   │   └── default.html
	│   │   │
	│   │   └── dairies
	│   │       ├── create.html
	│   │       ├── create.js
	│   │       ├── list.html
	│   │       └── list.js
	│   │
	│   └── app.html
	│
	└── public
	    └── images
	        └── logo.png

## Packages used

* iron:router
* zimme:iron-router-active
* sacha:spin
* aldeed:collection2
* twbs:bootstrap
* accounts-facebook
* accounts-twitter
* accounts-google
* ian:accounts-ui-bootstrap-3

## Made with Meteor

Meteor is an ultra-simple environment for building modern web
applications.

With Meteor you write apps:

* in pure JavaScript
* that send data over the wire, rather than HTML
* using your choice of popular open-source libraries

Documentation is available at http://docs.meteor.com/


## License

Copyright (c) 2015 Atul Yadav http://github.com/atulmy

The MIT License (http://www.opensource.org/licenses/mit-license.php)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
