# ZF2 Modules Site
Version 0.0.1

## Introduction

This site will eventually be a community site for publishing and sharing Zend Framework modules.

##Installation

###Main Setup

 * Clone this project into your ./vendor/ directory and enable it in your application.config.php file.
 * Run **git submodule update --init** to initialize your vendors
 * Import data/0.sql into your database
 * Create a new Application in github here. https://github.com/settings/applications/new
    * Main URL and CALLBACK url must be the same without any routing. e.g. http://modules.zendframework.com
 * Copy config/autoload/github.local.php.dist to config/autoload/github.local.php and enter the Id and Secret provided during the Application registration on github.
 * Copy config/autoload/database.local.php.dist to config/autoload/database.local.php and enter your database credentials here.

## Deployment

The master branch of this repository is automatically deployed live to
[modules.zendframework.com](http://modules.zendframework.com/) every 10
minutes.
