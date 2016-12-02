# JC-Firebase-PHP
PHP library access Firebase RESTful API

[![Packagist](https://img.shields.io/packagist/v/jaredchu/JC-Firebase-PHP.svg)](https://packagist.org/packages/jaredchu/jc-firebase-php)
[![Travis branch](https://img.shields.io/travis/jaredchu/JC-Firebase-PHP/master.svg)](https://travis-ci.org/jaredchu/JC-Firebase-PHP)
[![Scrutinizer](https://img.shields.io/scrutinizer/g/jaredchu/JC-Firebase-PHP.svg)](https://scrutinizer-ci.com/g/jaredchu/JC-Firebase-PHP/)
[![Scrutinizer branch](https://img.shields.io/scrutinizer/coverage/g/jaredchu/JC-Firebase-PHP/master.svg)](https://scrutinizer-ci.com/g/jaredchu/JC-Firebase-PHP/)

## Installation
composer require jaredchu/jc-firebase-php

## Usage
```php
<?php
    use JCFirebase\JCFirebase;
    $firebase = new JCFirebase('https://your-firebase-url',array('secret'=>'xxx','uid'=>'xxx'));
    $response = $firebase->get();
    echo $response->status_code;
    echo $response->body;
?>
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b feature/your-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-new-feature`
5. Submit a pull request.

## License
MIT License
