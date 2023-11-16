PHP Contracts
=============

A curated list of mature interfaces to build components on.

Good interfaces behave like a contract, a promise, a documentation. They don't have an opinion about the internals of a concrete implementation.
So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability,
interchangeability and maintainability.

**Rules:**

1. A project must only consist of interfaces that have the character of a contract.
2. The project must ship a good documentation.
3. The project could include one or more implementations.
4. The project's documentation must use english language.
5. The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/).
6. The interface(s) should comply with [PSR-12](https://www.php-fig.org/psr/psr-12/).
7. There should exist implementations that show the practical benefit of the offered interface(s).
8. The project should be available through [Packagist](https://packagist.org/).


## Stable

(Click on an item to get a list of available implementations)

| Project | Latest    | Implementations |
|---------|-----------|-----------------|
| [Logger Interface (PSR-03)](https://www.php-fig.org/psr/psr-3/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/log)](https://packagist.org/packages/psr/log) | [Compatible Packages](https://packagist.org/packages/psr/log) |
| [Simple Cache (PSR-16)](https://www.php-fig.org/psr/psr-16/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/simple-cache)](https://packagist.org/packages/psr/simple-cache) | [Compatible Packages](https://packagist.org/packages/psr/simple-cache) |
| [Caching Interface (PSR-06)](https://www.php-fig.org/psr/psr-6/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/cache)](https://packagist.org/packages/psr/cache) | [Compatible Packages](https://packagist.org/packages/psr/cache) |
| [Container Interface (PSR-11)](https://www.php-fig.org/psr/psr-11/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/container)](https://packagist.org/packages/psr/container) | [Compatible Packages](https://packagist.org/packages/psr/container) |
| [HTTP Message Interface (PSR-07)](https://www.php-fig.org/psr/psr-7/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-message)](https://packagist.org/packages/psr/http-message) | [Compatible Packages](https://packagist.org/packages/psr/http-message) |
| [HTTP-Client (PSR-18)](https://www.php-fig.org/psr/psr-18/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-client)](https://packagist.org/packages/psr/http-client) | [Compatible Packages](https://packagist.org/packages/psr/http-client) |
| [HTTP Server-Handler (PSR-15)](https://www.php-fig.org/psr/psr-15/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-server-handler)](https://packagist.org/packages/psr/http-server-handler) | [Compatible Packages](https://packagist.org/packages/psr/http-server-handler) |
| [HTTP Factories (PSR-17)](https://www.php-fig.org/psr/psr-17/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-factory)](https://packagist.org/packages/psr/http-factory) | [Compatible Packages](https://packagist.org/packages/psr/http-factory) |
| [Hypermedia Links (PSR-13)](https://www.php-fig.org/psr/psr-13/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/link)](https://packagist.org/packages/psr/link) | [Compatible Packages](https://packagist.org/packages/psr/link) |
| [Event Dispatcher (PSR-14)](https://www.php-fig.org/psr/psr-14/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/event-dispatcher)](https://packagist.org/packages/psr/event-dispatcher) | [Compatible Packages](https://packagist.org/packages/psr/event-dispatcher) |
| [Clock (PSR-20)](https://www.php-fig.org/psr/psr-20/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/clock)](https://packagist.org/packages/psr/clock) | [Compatible Packages](https://packagist.org/packages/psr/clock) |

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
* (More) Communication (Email, Sms, Notifications etc.)
* (More) Date-, Time-, Interval-, Calendar-Manipulation
* (More) Dependency-Injection-Container interfaces with more methods (make, call etc.)
* E-Commerce (Payment, common order structures, common address structures etc.)
* FileSystem-Abstraction
* Filetype-Abstraction
* Filtering
* Image-Manipulation
* Key-Value-Stores
* ORM / Data-Handling / Data-Structures
* Queues (like RabbitMQ / Gearman)
* Search-Server-Interfaces (querying, Responses, Facettes etc)
* Template-Engines
* URL-Manipulation
* Validation

