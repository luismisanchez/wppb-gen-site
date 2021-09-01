[![Dependency Status](https://david-dm.org/tmeister/wppb-gen-site.svg)](https://david-dm.org/tmeister/wppb-gen-site)

All credits shoud go to https://github.com/Tmeister. Thanks for the good job mate!

If you are planning to use this fork you should consider that the plugin source code is downloaded from my own fork
(https://github.com/luismisanchez/WordPress-Plugin-Boilerplate) not the original one (https://github.com/DevinVinson/WordPress-Plugin-Boilerplate)

Thanks too https://github.com/DevinVinson for the original Boilerplate. Amazing job.

Changes would be documented on this Readme file. See [changelog](#changelog). 
___

# WordPress Plugin Boilerplate Generator

A Node.js small application to generate a custom zip file based on the WPPB by Tom McFarlin ( [wppb.io](http://wppb.io) ).

This app will find and replace plugin-name, Plugin_Name, plugin_name and author information from the original code and will send a zip file with the new code, ready to use.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed.

```sh
$ git clone git@github.com:luismisanchez/wppb-gen-site.git # or clone your own fork
$ cd wppb-gen-site
$ npm install
$ node server
```

Your app should now be running on [localhost:3000](http://localhost:3000/).

Comments and requests at [@tmeister](https://twitter.com/tmeister) or noone at tmeister dot net

# <a name="changelog"></a>Changelog

* 09/01/2021
  - Added Update URI field. Since WP 5.8. See https://make.wordpress.org/core/2021/06/29/introducing-update-uri-plugin-header-in-wordpress-5-8/
* 08/31/2021 
    - Forked from https://github.com/Tmeister/wppb-gen-site
    - Added Description field
---
* (3 July 2015). Flattened the folder structure so there is no .org repo parent folder.
* (4 September 2014). Updating the `README` with Windows symbolic link instructions.
* (3 September 2014). Updating the `README` to describe how to install the Boilerplate.
* (1 September 2014). Initial Release.

