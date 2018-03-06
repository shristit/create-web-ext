# create-web-ext

[`create-web-ext`](https://www.npmjs.com/package/create-web-ext/) is a scaffolding tool for browser extensions. It takes input few parameters and outputs a complete scaffolded browser extension project.

## Requirements

* You need [Node.js](https://nodejs.org/en/) , 6.0.0 or higher
* Install [npm](https://www.npmjs.com/) , 3.0.0 or higher is recommended

Optionally, you may like:
* [nvm](https://github.com/creationix/nvm), which helps manage node versions

If you had already installed `create-web-ext` from npm,
you may need to uninstall it first:

    $ npm uninstall --global create-web-ext

Change into the source and install all dependencies:

    $ git clone https://github.com/web-ext-labs/create-web-ext.git
    $ cd create-web-ext
    $ npm install

Testing

    $ npm test

Link it to your node installation:

    $ npm link

You are all set, check

    $ create-web-ext -v

You can now run it from any directory.

## Web-extension Structure

Here is the created skeleton for your webextension with name for example `myAddon` when you selected all options : 

```text
myAddon
   ├── background_script.js
   ├── browserAction
   │   ├── index.html
   │   ├── script.js
   │   └── style.css
   ├── content_script.js
   ├── icons
   │   └── icon.png
   ├── manifest.json
   ├── options
   │   ├── index.html
   │   ├── script.js
   │   └── style.css
   └── pageAction
       ├── index.html
       ├── script.js
       └── style.css
```
