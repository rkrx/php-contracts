php contracts
=============

A curated list of mature interfaces to build components on.

Interfaces are still not very popular in the php-world. That is sad. They give you an absolute level of abstraction. Good interfaces behave like a contract, like a promise, like a documentation. They don't have a opinion about a concrete implementation. So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability, interchangeability and maintainability.

Rules:

* A project must only consist of interfaces that have the character of a contract.
* The project must ship a good documentation.
* The project must not include an implementation.
* The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/) and [PSR-2](http://www.php-fig.org/psr/psr-2/).
* There should exist implementations that show the practical benefit of the offered interface(s).
* The project should be available through packagist.


## Stable

| Project | Composer | Available components |
|---------|--------|----------|----------------------|
| [psr/log](https://github.com/php-fig/log) | "psr/log": "1.0.0" | [Monolog](https://github.com/Seldaek/monolog), [KLogger](https://github.com/katzgrau/KLogger) |
| [container-interop/container-interop](https://github.com/container-interop/container-interop) | "container-interop/container-interop": "1.0.0" | [Acclimate](https://github.com/jeremeamia/acclimate-container), [dcp-di](https://github.com/estelsmith/dcp-di), [Mouf](http://mouf-php.com/), [Njasm Container](https://github.com/njasm/container), [PHP-DI](http://php-di.org/), [PimpleInterop](https://github.com/moufmouf/pimple-interop), [XStatic](https://github.com/jeremeamia/xstatic) |


## Unstable

| Project | Composer | Available components |
|---------|--------|----------|----------------------|
| [psr/http-message](https://github.com/php-fig/http-message) | "psr/http-message": "1.0.*@dev" | |
| [psr/cache](https://github.com/php-fig/psr-6) | | |


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