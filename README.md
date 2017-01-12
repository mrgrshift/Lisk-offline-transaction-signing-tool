# Lisk offline transaction signing tool
Tool to sign offline the Lisk cryptocurrency transactions and optionally tool to broadcast online

Signing transaction is based on "lisk-js" library, FileSaver and jquery
https://github.com/LiskHQ/lisk-js
https://jquery.com
https://github.com/eligrey/FileSaver.js/

# Installtion
Download the offline.zip for your offline machine and online.zip for online machine - https://github.com/biolypl/Lisk-offline-transaction-signing-tool/releases/tag/v1.0

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
Download the latest [FileSaver.js](https://github.com/eligrey/FileSaver.js/), save the FileSaver.js in the same directory as offline.html and add the file in "head" section of offline.html with:
```js
<script src="FileSaver.js"></script>
```
Remember to edit the offline.html if you use another version of jquery than jquery-3.1.1.js

The same procedure as above is for online.html


## Author
bioly, terazbitcoin@gmail.com

Please consider voting me as a Lisk delegate, this will help me improve the tool and work more for Lisk community 
