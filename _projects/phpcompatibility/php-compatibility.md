---
layout:             'project'
title:              'PHPCompatibility'
order:              'phpcompatibility'
tags:               ['coding standards', 'php compatibility', 'cli']

authors:            [{name: 'Wim Godden'}, {name: 'Juliette Reinders Folmer'}] 

website:            [{url: 'https://github.com/PHPCompatibility/PHPCompatibility'}]
license:            [{url: 'https://github.com/PHPCompatibility/PHPCompatibility/blob/master/LICENSE', label: 'GNU Lesser General Public License v3.0 (LGPL)'}]

github:             [{name: 'PHPCompatibility/PHPCompatibility'}]
packagist:          [{name: 'phpcompatibility/php-compatibility'}]               
dockerhub:          [{name: 'phpqa/php-compatibility'}]     

dependencies:       []
composer-dev:       {further-instructions: {'Inform PHPCS about the new standard': 'php vendor/bin/phpcs --config-set installed_paths vendor/phpcompatibility/php-compatibility/PHPCompatibility'}, command: 'vendor/bin/phpcs --standard=PHPCompatibility'} 

---

[{{ page.title }}]({{ page.url | absolute_url }}) is a set of sniffs for PHP_CodeSniffer that checks for PHP version compatibility.

<!--more--> 

It will allow you to analyse your code for compatibility with higher and lower versions of PHP.
