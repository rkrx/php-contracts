php contracts
=============

A curated list of mature interfaces to build components on.

Interfaces are still not very popular in the php-world. That is sad. Interfaces give you an absolute level of abstraction. Good interfaces behave like a contract, a promise, a documentation. They don't have a opinion about a concrete implementation. So you can use interfaces while building huge applications to decouple different parts and hopefully gain a much better level of reusability, interchangeability and maintainability.

Rules:

* A project must only consist of interfaces that have the character of a contract.
* The project must ship a good documentation.
* The project must not include an implementation.
* The interface(s) must comply with [PSR-1](http://www.php-fig.org/psr/psr-1/) and [PSR-2](http://www.php-fig.org/psr/psr-2/).
* There should exist implementations that show the practical benefit of the offered interface(s).
* The project should be available through packagist.


## Stable

(Klick on an item to get a list of available implementations)

| Project | Composer |
|---------|---------|
| [psr/log](components/psr.log.md) | "psr/log": "1.0.0" |
| [container-interop/container-interop](components/container-interop.container-interop.md) | "container-interop/container-interop": "1.0.0" |


## Unstable

| Project | Composer | Status |
|---------|----------|--------|
| [adammbalogh/key-value-store](components/adammbalogh.key-value-store.md) | "adammbalogh/key-value-store": "0.5.2" | Unstable |
| [psr/http-message](https://github.com/php-fig/http-message) | "psr/http-message": "1.0.*@dev" | Unstable |
| [psr/cache](https://github.com/php-fig/psr-6) | | Unstable |


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

### Available components

* [Monolog](https://github.com/Seldaek/monolog)
* [KLogger](https://github.com/katzgrau/KLogger)

## container-interop/container-interop

[Project homepage](https://github.com/container-interop/container-interop)

### Available components

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

### Available components

* [adammbalogh/key-value-store (Various Adapters)](https://github.com/adammbalogh/key-value-store#adapters)