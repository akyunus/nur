# nur
```
       _ __  _   _ _ __
      | '_ \| | | | '__|
      | | | | |_| | |   
      |_| |_|\__,_|_|   
```
nur - simple framework for PHP

[![Total Downloads](https://poser.pugx.org/izniburak/nur-core/d/total.svg)](https://packagist.org/packages/izniburak/nur)
[![Latest Stable Version](https://poser.pugx.org/izniburak/nur-core/v/stable.svg)](https://packagist.org/packages/izniburak/nur)
[![Latest Unstable Version](https://poser.pugx.org/izniburak/nur-core/v/unstable.svg)](https://packagist.org/packages/izniburak/nur)
[![License](https://poser.pugx.org/izniburak/nur/license.svg)](https://packagist.org/packages/izniburak/nur)

> Nur Framework can be a preference for your small (maybe medium) projects. If you say; "I'll make a bigger project.", I suggest you use a full-stack framework. :) e.g: Symfony, Laravel...

### Features
- Model - View - Controller
- Easy command line application support. _(NUR Cli App)_
- Routing system and basic Middleware support. ([PHP-Router](https://github.com/izniburak/php-router))
- Symfony Request and Response components. ([Symfony HttpFoundation](https://symfony.com/doc/current/components/http_foundation.html))
- PDOx Query Builder Class. ([PDOx](https://github.com/izniburak/pdox))
- Some **Laravel 5.7** Packages supports.
    - Eloquent ORM support. ([Laravel Eloquent ORM](https://laravel.com/docs/eloquent))
    - Laravel Query Builder support. ([Laravel Query Builder](https://laravel.com/docs/queries))
    - Blade Template Engine support. ([Laravel Blade](https://laravel.com/docs/blade))
    - Laravel Eloquent Migration System support with PHPMig. ([Laravel Migration](https://laravel.com/docs/migrations) - [PHPMig](https://github.com/izniburak/nur-migration))
    - Collections support. ([Laravel Collections](https://laravel.com/docs/collections))
    - Useful array and string helpers. ([Laravel Helpers](https://laravel.com/docs/helpers))
- Events/Listeners, Basic logger, Request validation, Html/Form builder, Simple cache, Hashing etc...

## nur core
If you want to examine Nur's core files, you can follow this link: 

[izniburak/nur-core](https://github.com/izniburak/nur-core) 

## server requirements
- PHP >= 7.1.3
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension
- Ctype PHP Extension
- JSON PHP Extension

## install
create project via composer ("app" is application folder name):
```
$ composer create-project izniburak/nur app
$ cd app
$ cp .env.example .env
$ php nur
```

or run the following command directly.

```
$ git clone https://github.com/izniburak/nur.git
$ cd nur
$ composer install
$ cp .env.example .env
$ php nur
```

## docs
documentation page: [nur docs][doc-url] (coming soon...)

## todo
- Write test
- Write documentation
- ...

## support
[izniburak's homepage][author-url]

[izniburak's twitter][twitter-url]

## contributing
1. fork it [Nur Framework](https://github.com/izniburak/nur/fork) or [Nur Framework Core](https://github.com/izniburak/nur-core/fork) (for core changes)
2. create your feature branch (git checkout -b my-new-feature)
3. commit your changes (git commit -am 'Add some feature')
4. push to the branch (git push origin my-new-feature)
5. create a new Pull Request

## contributors
- [izniburak](https://github.com/izniburak) izni burak demirtaş - creator, maintainer

[paypal-donate-url]: http://burakdemirtas.org
[mit-url]: http://opensource.org/licenses/MIT
[doc-url]: javascript:;
[author-url]: http://burakdemirtas.org
[twitter-url]: https://twitter.com/izniburak
