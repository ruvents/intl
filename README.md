Symfony Intl Component Russian edition
======================================

This fork is the Russian edition of the [Symfony Intl Component](https://symfony.com/doc/current/components/intl.html).

This package [replaces](https://getcomposer.org/doc/04-schema.md#replace) the `symfony/intl` package. It means that packages requiring the original Symfony package will continue to work with this one.

For versioning we use __symfony version + 10__ rule. So instead of `composer require symfony/intl:^4.1` use `composer require ruwork/symfony-intl-russian:^14.1`.

Installation
------------

```bash
composer require ruwork/symfony-intl-russian
```

Changes
-------

```diff
+   "AB": "Abkhazia",
+   "OS": "South Ossetia",
```
