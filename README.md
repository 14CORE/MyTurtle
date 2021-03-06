MyTurtle
========

A modular HTML5 interface to display "turtles" on a digital signage template. Turtles included. This code should run on an external server, which makes it possible to maintain your digital signage solution into the cloud.

This is a project by [FlatTurtle](http://flatturtle.com). It's the back-end for our digital signage platform. FlatTurtle is a member of the [iRail npo](http://hello.iRail.be).

Features
========

 * plug-ins in javascript take care of special actions
 * API for real-time changes in the API
 * Add classes in the turtles directory and use them instantly
 * cronjobs

Useful links
============

* [Installation](https://github.com/FlatTurtle/MyTurtle/blob/master/INSTALL.md#installation)
* [Make your own](https://github.com/FlatTurtle/MyTurtle/blob/master/DEVELOPMENT.md#development)

Tools used
==========

 * jQuery
 * Backbone.js
 * Later.js: for cronjobs when the code is ran on TurtleOS using the [FlatTurtle InfoScreenBrowser](https://github.com/FlatTurtle/InfoScreenBrowser)
 * PHP5.3 with CodeIgniter prints the right configuration from the database as an initializer, and takes care of the URL structure. It does however not work as an API.

License and copyrights
======================

© 2011 - 2014 FlatTurtle bvba - Some rights reserved: AGPLv3
