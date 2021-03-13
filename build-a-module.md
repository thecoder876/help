# Build a module

1. Make a folder in the modules folder called whatever you want.
2. Add a file called `index.js`
3. Add the following code to the file:

```javascript
module.exports = function(host, res, req, error, version, ejs){
 
}
```

4. In the blank space add your own [HTTP module](https://nodejs.dev/learn/the-nodejs-http-module) code, you can also get the host, use the error module, get the version, and use EJS.
5. Import the module by adding the folder name to modules.json by adding `local://foldername` to moduleList and adding `"yoursite"` to website and adding `"yoursite":"yourfolder"` to websiteData.
6. Run Wgytcraft.

It should work! Need help? Ask the community [here](https://github.com/wgytcraft/help/discussions).
