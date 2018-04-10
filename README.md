Skrumble Client Library for PHP
=================================

*This library requires a minimum PHP version of 5.6* 

This is the PHP client library to use of Skrumble's API. To use this, you'll need a Skrumble Developer Account. Sign up for [an account at developers.skrumble.com](https://developer.skrumble.com). This is currently under a beta release, see [contributing](contributing.md) for more information.

* [Installation](#installation)
* [Usage](#usage)
* [Coverage](#coverage)
* Contributing

Installation
------------

To use the client library you'll need to have an account [created on Skrumble Developer](https://developers.skrumble.com)

To install the PHP client library using Composer

```
    composer require skrumble/php-sdk
```

Usage
-----

If you're using composer, make sure the autoloader is included in your project's bootstrap file: 

```
    require_once "vendor/autoload.php";
```

Create a client with your Client key and secret

```
$client = new Skrumble\Client(CLIENT_KEY, CLIENT_SECRET);
``` 

Coverage
--------

To contribute to the library, docs, or examples, [create an issue][issues] or a pull request. Please only raise issues
about features marked as working in the [API coverage](#coverage) as the rest of the code is being updated.


License
-------

This library is released under the [MIT License][license]