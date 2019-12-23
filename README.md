# Guzaba 2 Documentation

## Overview

Guzaba 2 framework is a PHP framework targeting [Swoole 4.4+](https://www.swoole.co.uk/).

It adheres to the following PSRs:
- [PSR 7 - HTTP Messaging Interface](https://www.php-fig.org/psr/psr-7/)
- [PSR 11 - Container Interface](https://www.php-fig.org/psr/psr-11/)
- [PSR 15 - HTTP Handlers (Middleware)](https://www.php-fig.org/psr/psr-15/)

It works with:
- [PSR 3 - Logger Interface](https://www.php-fig.org/psr/psr-3/)

It will support:
- [PSR 14 - Event Dispatcher](https://www.php-fig.org/psr/psr-14/)
- [PSR 16 - Common Interface for Caching Libraries](https://www.php-fig.org/psr/psr-16/)
- [PSR 17 - HTTP Factories](https://www.php-fig.org/psr/psr-17/)


## Coding and naming standards, conventions
The following naming standards and best practices are to be followed in the Guzaba2 development:
- [PHP coding standard](https://github.com/AzonMedia/php-coding-standard)
- [PHP naming convention](https://github.com/AzonMedia/php-naming-convention)
- [PHP best coding practices](https://github.com/kenashkov/php-best-coding-practices)
- [PHP best practices](https://github.com/kenashkov/php-best-practices)
- [Database conventions](https://github.com/AzonMedia/database-conventions)
- SQL coding standard
- SQL naming standard
- SQL best practices


## Sample projects
- [GuzabaPlatform Skeleton](https://github.com/AzonMedia/guzaba-platform-skeleton)
- [GuzabaPlatform](https://github.com/azonmedia/guzaba-platform)
- [Glog](https://github.com/azonmedia/glog)

## Requirements
- PHP 7.4.0
- Swoole 4.4.14

## Optional requirements
- Mysql 8
- Redis 4

## Getting Started
- [Setup](./Setup/README.md)
- [Project Structure](./ProjectStructure/README.md)
- [Creating Controller](./CreatingController/README.md)
- [Configuration](./Configuration/README.md)
- [Services](./Services/README.md)

## Basic Topics
- [Basics](./Basics/README.md)
- [Initialization](./Initialization/README.md)
- [Configuration](./Configuration/README.md)
- [Exceptions](./Exceptions/README.md)
- [Controllers](./Controllers/README.md)
- [Models](./Models/README.md)
- [Middlewares](./Middlewares/README.md)

## Code Sections
- [Authentication](./Authentication/README.md)
- [Authorization](./Authorization/README.md)
    - [Roles](./Authorization/Roles/README.md)
    - [Users](./Authorization/Users/README.md)
    - [Providers](./Authorization/Providers/README.md)
        - [ACL](./Authorization/Providers/Acl/README.md)
        - [RBAC](./Authorization/Providers/Rbac/README.md)
        - [Bypass](./Authorization/Providers/Bypass/README.md)
- [Base](./Base/README.md)
- [Cache](./Cache/README.md)
- [Coroutine](./Coroutine/README.md)
- [Database](./Database/README.md)
    - [SQL](./Database/README.md)
        - [Mysql](./Database/SQL/Mysql/README.md)
        - [Postgresql](./Database/NoSQL/Postgresql/README.md)
    - [NoSQL](./Database/NoSQL/RAEDME.md)
        - [Redis](./Database/NoSQL/Redis/README.md)
        - [Mongo](./Database/NoSQL/Mongo/README.md)
- [Di](./Di/README.md)
- [Events](./Events/README.md)
- [Http](./Http/README.md)
- [Kernel](./Kernel/README.md)
- [MVC](./Mvc/README.md)
    - [ExecutorMiddleware](./Mvc/ExecutorMiddleware/README.md)
    - [Controller](./Mvc/Controller/README.md)
    - [ActiveRecordController](./Mvc/ActiveRecordController/README.md)
- [ORM](./Orm/README.md)
    - [Stores](./Orm/Stores/README.md)
        - [Memory](./Orm/Stores/Memory/README.md)
        - [Redis](./Orm/Stores/Redis/README.md)
        - [Mysql](./Orm/Stores/Mysql/README.md)
        - [Null](./Orm/Stores/Null/README.md)
    - [MetaStores](./Orm/MetaStores/README.md)
    - [ActiveRecord](./Orm/ActiveRecord/README.md)
    - [ActiveRecordDefaultController](./Orm/ActiveRecordDefaultController/README.md)
- [PsrCache](./PsrCache/README.md)
- [Routing](./Routing/README.md)
    - [ActiveRecordDefaultRoutingMap](./Routing/ActiveRecordDefaultRoutingMap/README.md)
    - [ControllerDefaultRoutingMap](./Routing/ControllerDefaultRoutingMap/README.md)
    - [RoutingMiddleware](./Routing/RoutingMiddleware/README.md)
- [Swoole](./Swoole/README.md)
- [Transactions](./Transactions/README.md)
- [Translator](./Translator/README.md)
- [Wrappers](./Wrappers/README.md)


## Dependencies
- [Azonmedia\Debug](https://github.com/AzonMedia/debug)
- [Azonmedia\Di](https://github.com/AzonMedia/di)
- [Azonmedia\Lock](https://github.com/AzonMedia/lock)
- [Azonmedia\Patterns](https://github.com/AzonMedia/patterns)
- [Azonmedia\PsrToSwoole](https://github.com/AzonMedia/psr-to-swoole)
- [Azonmedia\Reflection](https://github.com/AzonMedia/reflection)
- [Azonmedia\Registry](https://github.com/AzonMedia/registry)
- [Azonmedia\Routing](https://github.com/AzonMedia/routing)
- [Azonmedia\SwooleToPsr](https://github.com/AzonMedia/swoole-to-psr)
- [Azonmedia\SuperglobalWrappers](https://github.com/AzonMedia/superglobal-wrappers)
- [Azonmedia\UrlRewriting](https://github.com/AzonMedia/url-rewriting)
