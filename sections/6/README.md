###Step 6 - NodeJS:
Enter [NodeJS](http://nodejs.org/):

NodeJS allows you to write non-browser based applications in JavaScript. What kind of applications:

* Simple command line scripts
* Server Side Web Applications
* [Desktop Apps](https://nodesource.com/blog/node-desktop-applications)
* [Hardware](http://sbstjn.github.io/noduino/)

####Quick Exercise:

Start by clicking the install link on the  site

Got through the install procedure then create a file called `node_cli_test.js` on your desktop.

Copy and paste the following code on to your desktop:

```
var fs = require('fs');
console.log("About to create a file");
var file_loc = __dirname + '/node_test_file.txt';
fs.writeFileSync(file_loc, 'This is a test');
console.log("Successfully created a new file:", file_loc);
```

Open up your terminal and navigate to your desktop then type the following:

```
node ./node_cli_test.js
```

This should execute the code and create a file on your desktop.




####Using NPM:
NPM stands for **Node Package Manager**.
A "Package" is like an angular module. Its library of code to help you complete a task.
All of the 3rd party packages for NodeJS are managed on [https://www.npmjs.com/](https://www.npmjs.com/).

You will need to know how to install various packages using NPM. It is pretty simple, just type ` npm install package_name`.
For example:

`npm install underscore`

####Tutorials:
I don't have a lot of tutorials on NodeJS that I recomend but if you want to play around check out [http://nodeschool.io/#workshoppers](http://nodeschool.io/#workshoppers)

