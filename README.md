blade
=====

Use Laravel Blade templates as a standalone component without the full Laravel framework

Full documentation is available at http://duncan3dc.github.io/blade/  
PHPDoc API documentation is also available at [http://duncan3dc.github.io/blade/api/](http://duncan3dc.github.io/blade/api/namespaces/duncan3dc.Laravel.html)  

[![release](https://poser.pugx.org/duncan3dc/blade/version.svg)](https://packagist.org/packages/duncan3dc/blade)
[![build](https://travis-ci.org/duncan3dc/blade.svg?branch=master)](https://travis-ci.org/duncan3dc/blade)
[![coverage](https://codecov.io/gh/duncan3dc/blade/graph/badge.svg)](https://codecov.io/gh/duncan3dc/blade)


Quick Examples
--------------

Output the view from `/var/www/views/index.blade.php`:
```php
use duncan3dc\Laravel\BladeInstance;

$blade = new BladeInstance("/var/www/views", "/var/www/cache/views");

echo $blade->render("index");
```

There is also a static class available:
```php
use duncan3dc\Laravel\Blade;

echo Blade::render("index");
```


This fork
--------------

Tested with PHP 8.1.26