# bolha.com-notifier

This script sends you an email every time a provided search result changes.

Prerequisites
=============

Install php and curl, on ubuntu you can do it like this:

    $ sudo apt-get install php-cli curl

Install php packages required to run the script:

[install composer](https://getcomposer.org/doc/00-intro.md)

	$ php composer.phar install

Copy `config.json.dist` to `config.json` and fill in the configuration values with your favorite text editor

Running
=======

Run the script with:

    $ php notifier.php
