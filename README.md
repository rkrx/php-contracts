PHP Contracts
=============

A curated list of mature interfaces to build components on.

Join us in the Gitter chat room: [![Join the chat at https://gitter.im/rkrx/php-contracts](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rkrx/php-contracts)

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

| Project | Packagist | Implementations |
|---------|-----------|-----------------|
| [psr/log](https://github.com/php-fig/log) | [![Latest Stable](http://img.shields.io/packagist/v/psr/log.svg)](https://packagist.org/packages/psr/log) | [Compatible Packages](https://packagist.org/providers/psr/log-implementation) |
| [psr/cache](https://github.com/php-fig/cache) | [![Latest Stable](http://img.shields.io/packagist/v/psr/cache.svg)](https://packagist.org/packages/psr/cache) | [Compatible Packages](https://packagist.org/providers/psr/cache-implementation)
| [psr/container](https://github.com/php-fig/container) | [![Latest Stable](http://img.shields.io/packagist/v/psr/container.svg)](https://packagist.org/packages/psr/container) | [Compatible Packages](https://packagist.org/providers/psr/container-implementation) |
| [psr/http-message](https://github.com/php-fig/http-message) | [![Latest Stable](http://img.shields.io/packagist/v/psr/http-message.svg)](https://packagist.org/packages/psr/http-message) | [Compatible Packages](https://packagist.org/providers/psr/http-message-implementation) |
| [psr/http-server-handler](https://github.com/php-fig/http-server-handler) | [![Latest Stable](http://img.shields.io/packagist/v/psr/http-message.svg)](https://packagist.org/packages/psr/http-server-handler) | [Compatible Packages](https://packagist.org/providers/psr/http-server-handler) |
| [psr/link](https://github.com/php-fig/link) | [![Latest Stable](http://img.shields.io/packagist/v/psr/link.svg)](https://packagist.org/packages/psr/simple-cache) | [Compatible Packages](https://packagist.org/providers/psr/link-implementation) |
| [psr/simple-cache](https://github.com/php-fig/simple-cache) | [![Latest Stable](http://img.shields.io/packagist/v/psr/simple-cache.svg)](https://packagist.org/packages/psr/simple-cache) | [Compatible Packages](https://packagist.org/providers/psr/simple-cache-implementation) |
| [psr/container](https://github.com/php-fig/container) | [![Latest Stable](http://img.shields.io/packagist/v/psr/containser.svg)](https://packagist.org/packages/psr/container) | [Compatible Packages](https://packagist.org/providers/psr/container-implementation) |
| [flamecore/event-observer](https://github.com/FlameCore/EventObserver) | [![Latest Stable](http://img.shields.io/packagist/v/flamecore/event-observer.svg)](https://packagist.org/packages/flamecore/event-observer) | Compatible Packages |

## Drafts

| Project | Packagist | Status |
|---------|-----------|--------|
| [adammbalogh/key-value-store](https://github.com/adammbalogh/key-value-store) | [![Latest Stable](http://img.shields.io/packagist/v/adammbalogh/key-value-store.svg)](https://packagist.org/packages/adammbalogh/key-value-store) | Draft |
| [rkr/php-ioc-contract](https://packagist.org/packages/rkr/php-ioc-contract) | [![Latest Stable](http://img.shields.io/packagist/v/rkr/php-di-ioc-adapter.svg)](https://packagist.org/packages/rkr/php-di-ioc-adapter) | Draft |

## Noteworthy projects

* [illuminate/contracts](https://github.com/illuminate/contracts) – Subtree split of the Illuminate Contracts component (see laravel/framework)
* [HttpKernelInterface](https://github.com/symfony/symfony/blob/master/src/Symfony/Component/HttpKernel/HttpKernelInterface.php) – HttpKernelInterface handles a Request to convert it to a Response.
* [FlySystem](http://flysystem.thephpleague.com) – Flysystem is a filesystem abstraction which allows you to easily swap out a local filesystem for a remote one. Reducing technical debt and chance of vendor lock-in. 

## Wishlist

* 3rd Party APIs (Amazon, Google etc)
* Authentication
* Communication (Email, Sms, Notifications etc.)
* (More) Date-, Time-, Interval-, Calendar-Manipulation
* (More) Dependency-Injection-Container interfaces with more methods (make, call etc.)
* E-Commerce (Payment, common order structures, common address structures etc.)
* File-System-Abstraction
* Filetype-Abstraction
* Filtering
* HTTP-Routing (Lookup and Link-Generation)
* Image-Manipulation
* Key-Value-Stores
* ORM / Data-Handling / Data-Structures
* Queues (like RabbitMQ / Gearman)
* Search-Server-Interfaces (querying, Responses, Facettes etc)
* Template-Engines
* URL-Manipulation
* Validation

