# Lisk offline transaction signing tool
Tool to sign offline the Lisk cryptocurrency transactions and optionally tool to broadcast online

Signing transaction is based on "lisk-js" library and jquery
https://github.com/LiskHQ/lisk-js
https://jquery.com

# Installtion
Download the offline.zip for your offline machine and online.zip for online machine
Instead online.html you can also use my page http://tools.mylisk.com/online.html
# OR
Download offline.html and [jquery](https://jquery.com)
Install lisk-js module
```
npm install lisk-js
```
Create new.js file with this:
```js
var lisk = require('lisk-js');
```
Next install [browserify](http://browserify.org/) and compile the module, for Linux:
```
browserify new.js -o bundle.js
```
Remember to edit the offline.html if you use another version of jquery than jquery-3.1.1.js

The same procedure as above is for online.html


## Author
bioly, terazbitcoin@gmail.com
Please consider voting me as a Lisk delegate, this will help me improve the tool and work more for Lisk community 
