PHP Contracts
=============

A curated list of mature interfaces to build components on.

Join us in the Gitter chat room: [![Gitter chat](https://badges.gitter.im/rkrx/php-contracts.png)](https://gitter.im/rkrx/php-contracts)

Interfaces are still not very popular in the PHP-world. That is sad. They give you the ability to interchange components with the same interface.
Good interfaces behave like a contract, a promise, a documentation. They don't have an opinion about the internals of a concrete implementation.
So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability,
interchangeability and maintainability.

**Rules:**

1. A project must only consist of interfaces that have the character of a contract.
2. The project must ship a good documentation.
3. The project could include one or more implementations.
4. The project's documentation must use english language.
5. The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/).
6. The interface(s) should comply with [PSR-2](http://www.php-fig.org/psr/psr-2/).
7. There should exist implementations that show the practical benefit of the offered interface(s).
8. The project should be available through [Packagist](https://packagist.org/).


## Stable

(Click on an item to get a list of available implementations)

| Project | Packagist |
|---------|-----------|
| [psr/log](#psrlog) | [![Latest Stable](http://img.shields.io/packagist/v/psr/log.svg)](https://packagist.org/packages/psr/log) |
| [psr/http-message](https://github.com/php-fig/http-message) | [![Latest Stable](http://img.shields.io/packagist/v/psr/http-message.svg)](https://packagist.org/packages/psr/http-message) |
| [container-interop/container-interop](#container-interopcontainer-interop) | [![Latest Stable](http://img.shields.io/packagist/v/container-interop/container-interop.svg)](https://packagist.org/packages/container-interop/container-interop) |
| [flamecore/event-observer](https://github.com/FlameCore/EventObserver) | [![Latest Stable](http://img.shields.io/packagist/v/flamecore/event-observer.svg)](https://packagist.org/packages/flamecore/event-observer) |

## Drafts

| Project | Packagist | Status |
|---------|-----------|--------|
| [adammbalogh/key-value-store](#adammbaloghkey-value-store) | [![Latest Stable](http://img.shields.io/packagist/v/adammbalogh/key-value-store.svg)](https://packagist.org/packages/adammbalogh/key-value-store) | Draft |
| [psr/cache](https://github.com/php-fig/fig-standards/blob/master/proposed/cache.md) | | Draft |
| [rkr/php-ioc-contract](https://packagist.org/packages/rkr/php-ioc-contract) | [![Latest Stable](http://img.shields.io/packagist/v/rkr/php-di-ioc-adapter.svg)](https://packagist.org/packages/rkr/php-di-ioc-adapter) | Draft |


## Noteworthy projects

* [illuminate/contracts](https://github.com/illuminate/contracts) – Subtree split of the Illuminate Contracts component (see laravel/framework)
* [HttpKernelInterface](https://github.com/symfony/symfony/blob/master/src/Symfony/Component/HttpKernel/HttpKernelInterface.php) – HttpKernelInterface handles a Request to convert it to a Response.
* [FlySystem](http://flysystem.thephpleague.com) – Flysystem is a filesystem abstraction which allows you to easily swap out a local filesystem for a remote one. Reducing technical debt and chance of vendor lock-in. 

## Wishlist

* 3rd Party APIs (Amazon, Google etc)
* Authentication
* Caching
* Communication (Email, Sms, Notifications etc.)
* (More) Date-, Time-, Interval-, Calendar-Manipulation
* (More) Dependency-Injection-Container interfaces with more methods (make, call etc.)
* E-Commerce (Payment, common order structures, common address structures etc.)
* File-System-Abstraction
* Filetype-Abstraction
* Filtering
* HTTP-Clients
* HTTP-Routing (Lookup and Link-Generation)
* Image-Manipulation
* Key-Value-Stores
* ORM / Data-Handling / Data-Structures
* Queues (like RabbitMQ / Gearman)
* Search-Server-Interfaces (querying, Responses, Facettes etc)
* Template-Engines
* URL-Manipulation
* Validation


## The Contracts

### psr/log

[Project homepage](https://github.com/php-fig/log)

**Available components**

* [KLogger](https://github.com/katzgrau/KLogger)
* [Monolog](https://github.com/Seldaek/monolog)

### container-interop/container-interop

[Project homepage](https://github.com/container-interop/container-interop)

**Available components**

* [Acclimate](https://github.com/jeremeamia/acclimate-container)
* [dcp-di](https://github.com/estelsmith/dcp-di)
* [Mouf](http://mouf-php.com/)
* [Njasm Container](https://github.com/njasm/container)
* [PHP-DI](http://php-di.org/)
* [PimpleInterop](https://github.com/moufmouf/pimple-interop)
* [squirt](https://github.com/phlogisticfugu/squirt)
* [SUDA](https://github.com/guide42/suda)
* [XStatic](https://github.com/jeremeamia/xstatic)

### adammbalogh/key-value-store

[Project homepage](https://github.com/adammbalogh/key-value-store)

**Available components**

* [adammbalogh/key-value-store (Various Adapters)](https://github.com/adammbalogh/key-value-store#adapters)
