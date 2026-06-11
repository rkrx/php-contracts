PHP Contracts
=============

A curated list of PHP contract packages: small, stable interfaces that define how two pieces of code work together without forcing either side to depend on one concrete implementation.

Contracts are most useful at the boundaries of an application. A package can depend on an HTTP client contract such as [PSR-18](https://www.php-fig.org/psr/psr-18/) instead of depending directly on Guzzle, Symfony HttpClient or any other client. The application can then choose the implementation, swap it later, mock it in tests, or share code across frameworks with less friction.

This repository collects interface packages that are worth considering when designing those boundaries. It is not a list of every abstraction in the PHP ecosystem. The focus is on contracts that are documented, mature enough for real projects, and supported by practical implementations.

**Guidelines:**

1. The package must define a clear contract through one or more PHP interfaces.
2. The contract must describe behavior and expectations, not the internals of a specific implementation.
3. The interfaces must be usable without requiring a particular framework, service container or runtime.
4. Implementations may exist in the same ecosystem, but user code should be able to depend on the contract package alone.
5. The project must provide useful English documentation, including the purpose of the contract and the expectations for implementers.
6. The interfaces must comply with [PSR-1](https://www.php-fig.org/psr/psr-1/) and should comply with [PSR-12](https://www.php-fig.org/psr/psr-12/).
7. There should be real implementations or adapters that demonstrate the practical value of the contract.
8. The package should be available through [Packagist](https://packagist.org/) and follow normal Composer versioning practices.


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
| [HTTP Server-Middleware (PSR-15)](https://www.php-fig.org/psr/psr-15/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-server-middleware)](https://packagist.org/packages/psr/http-server-middleware) | [Compatible Packages](https://packagist.org/providers/psr/http-server-middleware-implementation) |
| [HTTP Factories (PSR-17)](https://www.php-fig.org/psr/psr-17/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/http-factory)](https://packagist.org/packages/psr/http-factory) | [Compatible Packages](https://packagist.org/packages/psr/http-factory) |
| [Hypermedia Links (PSR-13)](https://www.php-fig.org/psr/psr-13/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/link)](https://packagist.org/packages/psr/link) | [Compatible Packages](https://packagist.org/packages/psr/link) |
| [Event Dispatcher (PSR-14)](https://www.php-fig.org/psr/psr-14/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/event-dispatcher)](https://packagist.org/packages/psr/event-dispatcher) | [Compatible Packages](https://packagist.org/packages/psr/event-dispatcher) |
| [Clock (PSR-20)](https://www.php-fig.org/psr/psr-20/) | [![Latest Stable](https://img.shields.io/packagist/v/psr/clock)](https://packagist.org/packages/psr/clock) | [Compatible Packages](https://packagist.org/packages/psr/clock) |

## Contract-oriented packages

Not every useful PHP contract is a PSR. The following packages are still useful when their domain matches an application boundary, because they publish interfaces separately from implementations or are mostly contract packages.

| Project | Latest | Focus | Implementations / Notes |
|---------|--------|-------|-------------------------|
| [Symfony Cache Contracts](https://github.com/symfony/cache-contracts) | [![Latest Stable](https://img.shields.io/packagist/v/symfony/cache-contracts)](https://packagist.org/packages/symfony/cache-contracts) | Cache access with Symfony's cache semantics on top of PSR-6/PSR-16. | [Compatible Packages](https://packagist.org/providers/symfony/cache-implementation) |
| [Symfony Event Dispatcher Contracts](https://github.com/symfony/event-dispatcher-contracts) | [![Latest Stable](https://img.shields.io/packagist/v/symfony/event-dispatcher-contracts)](https://packagist.org/packages/symfony/event-dispatcher-contracts) | Event dispatching contract compatible with Symfony components and PSR-14. | [Compatible Packages](https://packagist.org/providers/symfony/event-dispatcher-implementation) |
| [Symfony HTTP Client Contracts](https://github.com/symfony/http-client-contracts) | [![Latest Stable](https://img.shields.io/packagist/v/symfony/http-client-contracts)](https://packagist.org/packages/symfony/http-client-contracts) | HTTP client contract for synchronous, asynchronous and streaming HTTP clients. | [Compatible Packages](https://packagist.org/providers/symfony/http-client-implementation) |
| [Symfony Service Contracts](https://github.com/symfony/service-contracts) | [![Latest Stable](https://img.shields.io/packagist/v/symfony/service-contracts)](https://packagist.org/packages/symfony/service-contracts) | Service and dependency-injection contracts built around PSR-11. | [Compatible Packages](https://packagist.org/providers/symfony/service-implementation) |
| [Symfony Translation Contracts](https://github.com/symfony/translation-contracts) | [![Latest Stable](https://img.shields.io/packagist/v/symfony/translation-contracts)](https://packagist.org/packages/symfony/translation-contracts) | Translation interfaces for framework-independent internationalization boundaries. | [Compatible Packages](https://packagist.org/providers/symfony/translation-implementation) |
| [HTTPlug](https://github.com/php-http/httplug) | [![Latest Stable](https://img.shields.io/packagist/v/php-http/httplug)](https://packagist.org/packages/php-http/httplug) | HTTP client abstraction built on PSR-7, especially useful for asynchronous clients. | [Compatible Packages](https://packagist.org/providers/php-http/client-implementation); prefer PSR-18 for purely synchronous HTTP clients. |
| [Doctrine Persistence](https://www.doctrine-project.org/projects/persistence.html) | [![Latest Stable](https://img.shields.io/packagist/v/doctrine/persistence)](https://packagist.org/packages/doctrine/persistence) | Shared persistence interfaces and base contracts for Doctrine object mappers. | Useful at Doctrine-style persistence boundaries, not as a general repository standard. |
| [Illuminate Contracts](https://github.com/illuminate/contracts) | [![Latest Stable](https://img.shields.io/packagist/v/illuminate/contracts)](https://packagist.org/packages/illuminate/contracts) | Broad Laravel ecosystem contracts for cache, container, events, queues, routing and more. | Best suited for Laravel-compatible packages and applications. |


## Noteworthy projects

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
