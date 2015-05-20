wkhtmltopdf
================

This repository contains the Centos 6.6 binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git branch.
To install the latest version, use '0.12.2.1'.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _amd64_ with:

    php composer.phar require "r424/wkhtmltopdf-amd64:0.12.2.1"

The binary will then be located at:

    vendor/r424/wkhtmltopdf-amd64/bin/wkhtmltopdf-amd64
And
    vendor/r424/wkhtmltopdf-amd64/bin/wkhtmltoimage-amd64


