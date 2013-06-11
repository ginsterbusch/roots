# Customized [Roots Theme](http://www.rootstheme.com/)

Roots is a starting WordPress theme made for developers that’s based on
[HTML5 Boilerplate](http://html5boilerplate.com/) and [Bootstrap from Twitter](http://twitter.github.com/bootstrap/).

Difference to the original: Adding and removing a few forced choices, esp. the cleanup stuff. Another goal: **proper** OOP Singleton patterns - removing all that moronic procedural crap which might - and always does! - lead to nasty accidents with multiple defined functions.. asides of being unreadable!


* Source: [https://github.com/retlehs/roots](https://github.com/retlehs/roots)
* Home Page: [http://www.rootstheme.com/](http://www.rootstheme.com/)


## Installation

* Clone the git repo - `git clone git://github.com/retlehs/roots.git` - or [download it](https://github.com/retlehs/roots/zipball/master)
* Reference the [theme activation](doc/activation.md) documentation to understand
everything that happens once you activate Roots

## Configuration

Edit `lib/config.php` to enable or disable support for various theme functions
and to define constants that are used throughout the theme.

Edit `lib/init.php` to setup custom navigation menus and post thumbnail sizes.

## Documentation

Take a look at the [documentation table of contents](doc/TOC.md).

## Features

* HTML5 Boilerplate’s markup
* Bootstrap from Twitter
* [Theme wrapper](doc/wrapper.md)
* Root relative URLs
* Clean URLs (no more `/wp-content/`)
* All static theme assets are rewritten to the website root (`/assets/css/`,
`/assets/img/`, and `/assets/js/`)
* Cleaner HTML output of navigation menus
* Cleaner output of `wp_head` and enqueued scripts/styles
* Posts use the [hNews](http://microformats.org/wiki/hnews) microformat
* [Multilingual ready](http://www.rootstheme.com/wpml/) (Brazilian Portuguese,
Bulgarian, Catalan, Danish, Dutch, English, Finnish, French, German, Hungarian,
Indonesian, Italian, Korean, Macedonian, Norwegian, Polish, Russian, Simplified
Chinese, Spanish, Swedish, Traditional Chinese, Turkish, Vietnamese)


## Work in Progress

* above mentioned Singleton / OOP patterns
* less excessive forced cleanup "choices"
* qTranslate compatiblity
* More fun with a working [HeadJS plugin](http://wordpress.org/plugins/asynchronous-javascript/) solution ;)



