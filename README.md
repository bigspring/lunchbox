Lunchbox
========

A composer config file that can get you up and running with WordPress and essential plugins in a few seconds. Automatically downloads WordPress and an essential arsenal of plugins (listed below).

Suggestions? Ideas? Submit an issue!

Built by the team at [BigSpring](https://github.com/bigspring). Composer config and companion installer [Munch](https://github.com/bigspring/munch) by [DM Seaton](https://github.com/dmseaton).

For project updates follow [@juliotaylor](http://twitter.com/juliotaylor) or [@bigspringweb](http://twitter.com/bigspringweb).

features
--------

Lunchbox will install the following packages:

* WordPress (latest stable build)
* Monolith WordPress starter theme (https://github.com/bigspring/monolith)
* YOAST WordPress SEO Plugin
* W3 Total Cache
* Force Regenrate Thumbnails
* Widget Logic
* Bulk Page Creator
* Breadcrumb NavXT
* Advanced Text Widget
* Contact Form 7
* Imsanity
* Better Wordpress Security
* WP Password Generator

If you'd like to request a plugin or feature, [create a new issue](https://github.com/bigspring/lunchbox/issues).

usage
------

It is recommended that you use the companion installer/project tool [Munch](https://github.com/bigspring/munch), although you can also install by placing composer.json in your webprojects root and running:

```
composer install
```

However, this will result in leftover Composer files.


achtung! danger!
------

We strongly advise you to take a look at the source before you run anything to make sure it does what you need. Lunchbox comes with no warranty whatsoever, so use at your own risk!


changelog
------

* 09/10/14 - v2.0.0 - refactored full process to utilise composer
* 14/08/13 - v1.1.0 - new command interface, with self-update and various other methods
* 13/08/13 - v1.0.7 - added support for WP Password Generator
* 13/08/13 - v1.0.6 - update readme, updated monolith package handling
* 12/08/13 - v1.0.5 - account for .bash_profile during installation
* 12/08/13 - v1.0.4 - updated path in readme and installation file
* 12/08/13 - v1.0.3 - hassle free installation
* 12/08/13 - v1.0.2 - updated monolith package to use master (v1.0)
* 12/08/13 - v1.0.1 – added support for smush.it, contact form 7, better WP security
* 08/08/13 - v1.0.0 – hello world!
