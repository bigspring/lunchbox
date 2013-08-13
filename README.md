Lunchbox
========

A clever little bash script for Mac OS X that gets you up and running with WordPress and essential plugins in a few seconds. Automatically downloads WordPress and an essential arsenal of plugins (listed below).

Suggestions? Ideas? Submit an issue!

Built by the team at [BigSpring](https://github.com/bigspring). Installer by [Martin Dines](https://github.com/martindines).

For project updates follow (@juliotaylor)[http://twitter.com/juliotaylor] or (@bigspringweb)[http://twitter.com/bigspringweb].

features
--------

Lunchbox will install the following things:

* WordPress (latest stable build)
* monolith WordPress starter theme (https://github.com/bigspring/monolith)
* YOAST WordPress SEO Plugin
* W3 Total Cache
* Force Regenrate Thumbnails
* Widget Logic
* Bulk Page Creator
* Breadcrumb NavXT
* Advanced Text Widget
* Contact Form 7
* WP Smush.it
* Better Wordpress Security
* WP Password Generator

If you'd like to request a plugin or feature, [create a new issue](https://github.com/bigspring/lunchbox/issues)


installation
------------

Step 1 - run either of the following commands

```
bash < <(wget -O - https://raw.github.com/bigspring/lunchbox/master/lunchbox-installer)
```

or

```
bash < <(curl -s https://raw.github.com/bigspring/lunchbox/master/lunchbox-installer)
```

Step 2 - run the following (change to `.profile` if `.bash_profile` does not exist)

```
source ~/.bash_profile
```

Note: Lunchbox is simply a bash script, so to use it you just need to place it in your $PATH and change its mode to executable.


usage
------

* in command line, navigate to the folder into which you want to install your site (e.g. ~/htdocs/mysite)
* run 'lunchbox' from command line from within the target directory
* wait for the lunchbox to unpack, and enjoy your lunch!


achtung! danger!
------

we strongly advise you to take a look at the source before you run anything to make sure it does what you need. lunchbox comes with no warranty whatsoever, so use at your own risk!


changelog
------

* 13/08/13 - v1.0.7 - added support for WP Password Generator
* 13/08/13 - v1.0.6 - update readme, updated monolith package handling
* 12/08/13 - v1.0.5 - account for .bash_profile during installation
* 12/08/13 - v1.0.4 - updated path in readme and installation file
* 12/08/13 - v1.0.3 - hassle free installation
* 12/08/13 - v1.0.2 - updated monolith package to use master (v1.0)
* 12/08/13 - v1.0.1 – added support for smush.it, contact form 7, better WP security
* 08/08/13 - v1.0.0 – hello world!