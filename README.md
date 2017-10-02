Class Pattern Sniff for PHP CodeSniffer
=====================================================
[![Build Status](https://travis-ci.org/terminus-est-gm/phpcs-classpattern.png?branch=master)](https://travis-ci.org/jrfnl/Google-WebDev-PHPCS)

## Introduction

This is a sniff for [PHP CodeSniffer](http://pear.php.net/PHP_CodeSniffer) which can be used to check that class names adhere to a pattern.

## Installation

### Requirements

* PHP 5.4+.
* [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer): 3.0.2+.

### Installation in a Composer project

* TBD.

### Standalone

1. TBD.


## Using a custom ruleset

Like with any PHP CodeSniffer standard, you can add this classpattern to a custom PHP CodeSniffer ruleset.

```xml
<?xml version="1.0"?>
<ruleset name="Custom ruleset">
    <description>My rules for PHP CodeSniffer</description>

    ClassPattern
    <rule ref="ClassPattern"/>

    <!-- Run against a second ruleset -->
    <rule ref="PSR2"/>

</ruleset>
```

## License

This code is released under the **_TBD_**.

## Thanks

So many thanks to Juliette Reinders Folmer for the use of her repo https://github.com/jrfnl/Google-WebDev-PHPCS to base 
my work from, and the awesome advice and guidance on this project. You inspired me. 
