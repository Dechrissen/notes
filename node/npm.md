# npm (Node Package Manager)
- Both:
    - a library of packages
    - also a **command line tool** to install/manage packages

## Installing / requiring
if you install a package with `npm install <package>` you can require it in a file in that project directory
```bash
npm install colors
```
then in some js file
```js
const colors = require('colors');

// and you can use it as normal
```

### npm init
- creates `package.json` in the project folder that conforms to the standard we should follow
```bash
npm init
```
- then, when you install other npm modules in the project folder, they will be added to the `package.json` dependencies list

### installing dependencies for a project
this installs all dependencies for a project (from a `package.json` file in a project directory)
```bash
npm install
```