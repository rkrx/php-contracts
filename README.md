php contracts
=============

A curated list of mature interfaces to build components on.

Interfaces are still not very popular in the php-world. That is sad. Interfaces give you an absolute level of abstraction. Good interfaces behave like a contract, a promise, a documentation. They don't have a opinion about a concrete implementation. So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability, interchangeability and maintainability.

Rules:

* A project must only consist of interfaces that have the character of a contract.
* The project must ship a good documentation.
* The project ~~must not~~ could include one or more implementations.
* The project's documentation must use englisch language.
* The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/) and [PSR-2](http://www.php-fig.org/psr/psr-2/).
* There should exist implementations that show the practical benefit of the offered interface(s).
* The project should be available through packagist.


## Stable

(Klick on an item to get a list of available implementations)

| Project | Composer |
|---------|---------|
| [psr/log](#psrlog) | "psr/log": "1.0.0" |
| [container-interop/container-interop](#container-interopcontainer-interop) | "container-interop/container-interop": "1.0.0" |


## Drafts

| Project | Composer | Status |
|---------|----------|--------|
| [adammbalogh/key-value-store](#adammbaloghkey-value-store) | "adammbalogh/key-value-store": "0.5.2" | Draft |
| [psr/http-message](https://github.com/php-fig/http-message) | "psr/http-message": "1.0.*@dev" | Draft |
| [psr/cache](https://github.com/php-fig/psr-6) | | Draft |
| [rkr/php-ioc-contract](https://packagist.org/packages/rkr/php-ioc-contract) | | Draft |


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
