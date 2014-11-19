php contracts
=============

A curated list of mature interfaces to build components on.

Interfaces are still not very popular in the php-world. That is sad. They give you the ability to interchange components with the same interface. Good interfaces behave like a contract, a promise, a documentation. They don't have an opinion about the internals of a concrete implementation. So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability, interchangeability and maintainability.

Rules:

* A project must only consist of interfaces that have the character of a contract.
* The project must ship a good documentation.
* The project could include one or more implementations.
* The project's documentation must use englisch language.
* The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/).
* The interface(s) should comply with [PSR-2](http://www.php-fig.org/psr/psr-2/).
* There should exist implementations that show the practical benefit of the offered interface(s).
* The project should be available through packagist.


## Stable

(Click on an item to get a list of available implementations)

| Project | Packagist |
|---------|---------|
| [psr/log](#psrlog) | [![Latest Stable](http://img.shields.io/packagist/v/psr/log.svg)](https://packagist.org/packages/psr/log) |
| [container-interop/container-interop](#container-interopcontainer-interop) | [![Latest Stable](http://img.shields.io/packagist/v/container-interop/container-interop.svg)](https://packagist.org/packages/container-interop/container-interop) |
| [flamecore/observer](https://github.com/FlameCore/Observer) | [![Latest Stable](http://img.shields.io/packagist/v/FlameCore/Observer.svg)](https://packagist.org/packages/flamecore/observer) |

## Drafts

| Project | Packagist | Status |
|---------|----------|--------|
| [adammbalogh/key-value-store](#adammbaloghkey-value-store) | [![Latest Stable](http://img.shields.io/packagist/v/adammbalogh/key-value-store.svg)](https://packagist.org/packages/adammbalogh/key-value-store) | Draft |
| [psr/http-message](https://github.com/php-fig/http-message) | [![Latest Stable](http://img.shields.io/packagist/v/psr/http-message.svg)](https://packagist.org/packages/psr/http-message) | Draft |
| [psr/cache](https://github.com/php-fig/psr-6) | | Draft |
| [rkr/php-ioc-contract](https://packagist.org/packages/rkr/php-ioc-contract) | [![Latest Stable](http://img.shields.io/packagist/v/rkr/php-di-ioc-adapter.svg)](https://packagist.org/packages/rkr/php-di-ioc-adapter) | Draft |

## Noteworthy projects

* [illuminate/contracts](https://github.com/illuminate/contracts)
* [HttpKernelInterface](https://github.com/symfony/symfony/blob/master/src/Symfony/Component/HttpKernel/HttpKernelInterface.php)

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
* ORM/Datahandling/Datastructures
* Queues (like RabbitMQ / Gearman)
* Search-Server-Interfaces (querying, Responses, Facettes etc)
* Template-Engines
* Url-Manipulation
* Validation

## psr/log

[Project homepage](https://github.com/php-fig/log)

**Available components**

* [KLogger](https://github.com/katzgrau/KLogger)
* [Monolog](https://github.com/Seldaek/monolog)

## container-interop/container-interop

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

## adammbalogh/key-value-store

[Project homepage](https://github.com/adammbalogh/key-value-store)

**Available components**

* [adammbalogh/key-value-store (Various Adapters)](https://github.com/adammbalogh/key-value-store#adapters)
