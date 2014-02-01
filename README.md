# BtMarkdown - ZF2 Markdown Parser Module

Version 1.0 Created by [Benjamin Tigano](http://benjamin-t.com/)

## Introduction

This ZF2 module is used for parsing [Markdown Extra](http://michelf.com/projects/php-markdown/extra/) syntax in your application. The awesome library that actually parses the markdown text was written by [Michel Fortin](http://michelf.com/).

## Installation

To install BtMarkdown, recursively clone this repository (`git clone
--recursive`) into your ZF2 modules directory or download and extract into
your ZF2 modules directory.

## Enable the module

Once you've installed the module, you need to enable it. You can do this by 
adding it to your `config/application.config.php` file:

```php
<?php
return array(
    'modules' => array(
        'Application',
        'BtMarkdown',
    ),
);
```

## Usage

In your view scripts, simply invoke the markdown view helper:

```php
<?= $this->markdown('_Markdown_ is super easy for **bold** and *italic* text.'); ?>
```

## License

BtMarkdown is released under a New BSD license. See the included LICENSE file.
