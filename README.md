# generator-prestamodule
Yeoman generator for PrestaShop module. It's support basic module class and also ObjectModel, FrontController and AdminController as well.

**It's full compatible with PrestaShop module's validator.**

## Installation

To use this generator you must install yeomangenerator if you haven't yet.

`npm install -g yo`

### Install with npm

Just type this command:

`npm install -g generator-prestamodule`

### Install manualy

Download [this repo](https://github.com/gladius882/generator-prestamodule) and run this command in root folder:

`npm link`

This will make generator visible for yo.

## Commands

- **yo prestamodule** - generate module's class and create directories with default index.php
- **yo prestamodule:ObjectModel** - generate basic class represantation of database table
- **yo prestamodule:AdminController** - generate basic AdminController page
- **yo prestamodule:FrontController** - generate basic FronController page

In case of any bugs or sugestions about updates feel free to create new [issue](https://github.com/gladius882/generator-prestamodule/issues)