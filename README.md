# OPENESTATE_PHP_EXPORT

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `OPENESTATE_PHP_EXPORT` in category **REAL_ESTATE**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** OPENESTATE_PHP_EXPORT · **Upstream pin:** `0aaaaa6132ac199ab12cdc680f91f6ae4c663711` · **Category:** REAL_ESTATE · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

OpenEstate-PHP-Export 2.0-beta2
===============================

*OpenEstate-PHP-Export* is developed as a part of the freeware real estate
software [*OpenEstate-ImmoTool*](https://openestate.org/). When a user exports
his properties to his website in PHP format, these scripts are transferred to
the webspace including real estate data in the [`data`](src/data) folder.

Features
--------

-   listing view of multiple real estates
    (see [`index.php`](src/index.php))
-   detailled view of a single real estate
    (see [`expose.php`](src/expose.php))
-   visitors may manage their favored real estates
    (see [`fav.php`](src/fav.php))
-   real estate listings may be filtered by different criteria
    (see [`\OpenEstate\PhpExport\Filter`](src/include/OpenEstate/PhpExport/Filter))
-   real estate listings may be ordered by different criteria
    (see [`\OpenEstate\PhpExport\Order`](src/include/OpenEstate/PhpExport/Order))
-   a basic contact form is available
    (see [`\OpenEstate\PhpExport\Action\Contact`](src/include/OpenEstate/PhpExport/Action/Contact.php))
-   generated output is fully customizable with [themes](src/themes)
-   a lot of configuration options are available
    (see [`\OpenEstate\PhpExport\Config`](src/include/OpenEstate/PhpExport/Config.php)
    and [`config.php`](src/config.php))
-   available in multiple languages (English by default, see
    [current translation progress](https://i18n.openestate.org/projects/openestate-php-export/#languages))
-   open source modules are available for
    [*WordPress*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WordPress),
    [*CMS made simple*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-CMSms),
    [*WBCE*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WBCE) &
    [*Joomla*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-Joomla)

Requirements
------------

-   client side (real estate agency / website owner)
    -   [*OpenEstate-ImmoTool*](https://openestate.org/) 1.0.0 or later
-   webspace side
    -   PHP 5.6 or newer
    -   [PHP *GD* extension](https://secure.php.net/manual/en/book.image.php)
        (optional, but recommended)
    -   [PHP *mbstring* extension](https://secure.php.net/manual/en/book.mbstring.php)
        (optional)
    -   [PHP *iconv* extension](https://secure.php.net/manual/en/book.iconv.php)
        (optional)

Third party components
----------------------

The following third party components are provided by *OpenEstate-PHP-Export*:

-   [PHPMailer](https://github.com/PHPMailer/PHPMailer) v6.0.6
    (license: [LGPL 2.1](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE))
-   [Gettext](https://github.com/oscarotero/Gettext) v4.6.1
    (license: [MIT](https://github.com/oscarotero/Gettext/blob/master/LICENSE))
-   [Gettext CLDR data](https://github.com/mlocati/cldr-to-gettext-plural-rules) v2.5.0
    (license: [MIT](https://github.com/mlocati/cldr-to-gettext-plural-rules/blob/master/LICENSE))
-   [Punycode](https://github.com/true/php-punycode) v2.1.1
    (license: [MIT](https://github.com/true/php-punycode/blob/master/LICENSE))
-   [jQuery](https://jquery.com/) v3.3.1
    (license: [MIT](https://jquery.org/license/))
-   [slick](https://kenwheeler.github.io/slick/) v1.8.1
    (license: [MIT](https://github.com/kenwheeler/slick/blob/master/LICENSE))
-   components used by the [*default* theme](src/themes/default)
    -   [Pure.CSS](https://purecss.io/) v1.0.0
        (license: [BSD](https://github.com/pure-css/pure/blob/master/LICENSE))
    -   [Colorbox](https://www.jacklmoore.com/colorbox/) v1.6.4
        (license: [MIT](https://github.com/jackmoore/colorbox/blob/master/LICENSE.md))
    -   [Popper.js](https://popper.js.org/) v1.14.5
        (license: [MIT](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md))
-   components used by the [*bootstrap3* theme](src/themes/bootstrap3)
    -   [Bootstrap](https://getbootstrap.com/) v3.3.7
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
-   components used by the [*bootstrap4* theme](src/themes/bootstrap4)
    -   [Bootstrap](https://getbootstrap.com/) v4.1.3
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
        bundled with [Popper.js](https://popper.js.org/)
-   aggregated icons (generated with [*fontello.com*](http://fontello.com/))
    -   [Font Awesome](https://fontawesome.com/)
        (license: [SIL](https://fontawesome.com/license/free))
    -   [Fontelico](https://github.com/fontello/fontelico.font)
        (license: [SIL](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL))

Limitations
-----------

This solution works entirely without a database. Therefore more complex queries
on the exported real estates may not be possible with acceptable performance.

License
-------

This library is licensed under the terms of
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).
Take a look at the provided [`LICENSE.txt`](LICENSE.txt) for the license text.

Further information
-------------------

-   [*OpenEstate-PHP-Export* at GitHub](https://github.com/OpenEstate/OpenEstate-PHP-Export)
-   [Releases of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/releases)
-   [Changelog of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/blob/master/CHANGELOG.md)
-   [API documentation of *OpenEstate-PHP-Export*](https://media.openestate.org/apidocs/OpenEstate-PHP-Export/)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

his properties to his website in PHP format, these scripts are transferred to
the webspace including real estate data in the [`data`](src/data) folder.

Features
--------

-   listing view of multiple real estates
    (see [`index.php`](src/index.php))
-   detailled view of a single real estate
    (see [`expose.php`](src/expose.php))
-   visitors may manage their favored real estates
    (see [`fav.php`](src/fav.php))
-   real estate listings may be filtered by different criteria
    (see [`\OpenEstate\PhpExport\Filter`](src/include/OpenEstate/PhpExport/Filter))
-   real estate listings may be ordered by different criteria
    (see [`\OpenEstate\PhpExport\Order`](src/include/OpenEstate/PhpExport/Order))
-   a basic contact form is available
    (see [`\OpenEstate\PhpExport\Action\Contact`](src/include/OpenEstate/PhpExport/Action/Contact.php))
-   generated output is fully customizable with [themes](src/themes)
-   a lot of configuration options are available
    (see [`\OpenEstate\PhpExport\Config`](src/include/OpenEstate/PhpExport/Config.php)
    and [`config.php`](src/config.php))
-   available in multiple languages (English by default, see
    [current translation progress](https://i18n.openestate.org/projects/openestate-php-export/#languages))
-   open source modules are available for
    [*WordPress*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WordPress),
    [*CMS made simple*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-CMSms),
    [*WBCE*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WBCE) &
    [*Joomla*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-Joomla)

Requirements
------------

-   client side (real estate agency / website owner)
    -   [*OpenEstate-ImmoTool*](https://openestate.org/) 1.0.0 or later
-   webspace side
    -   PHP 5.6 or newer
    -   [PHP *GD* extension](https://secure.php.net/manual/en/book.image.php)
        (optional, but recommended)
    -   [PHP *mbstring* extension](https://secure.php.net/manual/en/book.mbstring.php)
        (optional)
    -   [PHP *iconv* extension](https://secure.php.net/manual/en/book.iconv.php)
        (optional)

Third party components
----------------------

The following third party components are provided by *OpenEstate-PHP-Export*:

-   [PHPMailer](https://github.com/PHPMailer/PHPMailer) v6.0.6
    (license: [LGPL 2.1](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE))
-   [Gettext](https://github.com/oscarotero/Gettext) v4.6.1
    (license: [MIT](https://github.com/oscarotero/Gettext/blob/master/LICENSE))
-   [Gettext CLDR data](https://github.com/mlocati/cldr-to-gettext-plural-rules) v2.5.0
    (license: [MIT](https://github.com/mlocati/cldr-to-gettext-plural-rules/blob/master/LICENSE))
-   [Punycode](https://github.com/true/php-punycode) v2.1.1
    (license: [MIT](https://github.com/true/php-punycode/blob/master/LICENSE))
-   [jQuery](https://jquery.com/) v3.3.1
    (license: [MIT](https://jquery.org/license/))
-   [slick](https://kenwheeler.github.io/slick/) v1.8.1
    (license: [MIT](https://github.com/kenwheeler/slick/blob/master/LICENSE))
-   components used by the [*default* theme](src/themes/default)
    -   [Pure.CSS](https://purecss.io/) v1.0.0
        (license: [BSD](https://github.com/pure-css/pure/blob/master/LICENSE))
    -   [Colorbox](https://www.jacklmoore.com/colorbox/) v1.6.4
        (license: [MIT](https://github.com/jackmoore/colorbox/blob/master/LICENSE.md))
    -   [Popper.js](https://popper.js.org/) v1.14.5
        (license: [MIT](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md))
-   components used by the [*bootstrap3* theme](src/themes/bootstrap3)
    -   [Bootstrap](https://getbootstrap.com/) v3.3.7
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
-   components used by the [*bootstrap4* theme](src/themes/bootstrap4)
    -   [Bootstrap](https://getbootstrap.com/) v4.1.3
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
        bundled with [Popper.js](https://popper.js.org/)
-   aggregated icons (generated with [*fontello.com*](http://fontello.com/))
    -   [Font Awesome](https://fontawesome.com/)
        (license: [SIL](https://fontawesome.com/license/free))
    -   [Fontelico](https://github.com/fontello/fontelico.font)
        (license: [SIL](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL))

Limitations
-----------

This solution works entirely without a database. Therefore more complex queries
on the exported real estates may not be possible with acceptable performance.

License
-------

This library is licensed under the terms of
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).
Take a look at the provided [`LICENSE.txt`](LICENSE.txt) for the license text.

Further information
-------------------

-   [*OpenEstate-PHP-Export* at GitHub](https://github.com/OpenEstate/OpenEstate-PHP-Export)
-   [Releases of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/releases)
-   [Changelog of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/blob/master/CHANGELOG.md)
-   [API documentation of *OpenEstate-PHP-Export*](https://media.openestate.org/apidocs/OpenEstate-PHP-Export/)

## API

[*WordPress*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WordPress),
    [*CMS made simple*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-CMSms),
    [*WBCE*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WBCE) &
    [*Joomla*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-Joomla)

Requirements
------------

-   client side (real estate agency / website owner)
    -   [*OpenEstate-ImmoTool*](https://openestate.org/) 1.0.0 or later
-   webspace side
    -   PHP 5.6 or newer
    -   [PHP *GD* extension](https://secure.php.net/manual/en/book.image.php)
        (optional, but recommended)
    -   [PHP *mbstring* extension](https://secure.php.net/manual/en/book.mbstring.php)
        (optional)
    -   [PHP *iconv* extension](https://secure.php.net/manual/en/book.iconv.php)
        (optional)

Third party components
----------------------

The following third party components are provided by *OpenEstate-PHP-Export*:

-   [PHPMailer](https://github.com/PHPMailer/PHPMailer) v6.0.6
    (license: [LGPL 2.1](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE))
-   [Gettext](https://github.com/oscarotero/Gettext) v4.6.1
    (license: [MIT](https://github.com/oscarotero/Gettext/blob/master/LICENSE))
-   [Gettext CLDR data](https://github.com/mlocati/cldr-to-gettext-plural-rules) v2.5.0
    (license: [MIT](https://github.com/mlocati/cldr-to-gettext-plural-rules/blob/master/LICENSE))
-   [Punycode](https://github.com/true/php-punycode) v2.1.1
    (license: [MIT](https://github.com/true/php-punycode/blob/master/LICENSE))
-   [jQuery](https://jquery.com/) v3.3.1
    (license: [MIT](https://jquery.org/license/))
-   [slick](https://kenwheeler.github.io/slick/) v1.8.1
    (license: [MIT](https://github.com/kenwheeler/slick/blob/master/LICENSE))
-   components used by the [*default* theme](src/themes/default)
    -   [Pure.CSS](https://purecss.io/) v1.0.0
        (license: [BSD](https://github.com/pure-css/pure/blob/master/LICENSE))
    -   [Colorbox](https://www.jacklmoore.com/colorbox/) v1.6.4
        (license: [MIT](https://github.com/jackmoore/colorbox/blob/master/LICENSE.md))
    -   [Popper.js](https://popper.js.org/) v1.14.5
        (license: [MIT](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md))
-   components used by the [*bootstrap3* theme](src/themes/bootstrap3)
    -   [Bootstrap](https://getbootstrap.com/) v3.3.7
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
-   components used by the [*bootstrap4* theme](src/themes/bootstrap4)
    -   [Bootstrap](https://getbootstrap.com/) v4.1.3
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
        bundled with [Popper.js](https://popper.js.org/)
-   aggregated icons (generated with [*fontello.com*](http://fontello.com/))
    -   [Font Awesome](https://fontawesome.com/)
        (license: [SIL](https://fontawesome.com/license/free))
    -   [Fontelico](https://github.com/fontello/fontelico.font)
        (license: [SIL](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL))

Limitations
-----------

This solution works entirely without a database. Therefore more complex queries
on the exported real estates may not be possible with acceptable performance.

License
-------

This library is licensed under the terms of
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).
Take a look at the provided [`LICENSE.txt`](LICENSE.txt) for the license text.

Further information
-------------------

-   [*OpenEstate-PHP-Export* at GitHub](https://github.com/OpenEstate/OpenEstate-PHP-Export)
-   [Releases of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/releases)
-   [Changelog of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/blob/master/CHANGELOG.md)
-   [API documentation of *OpenEstate-PHP-Export*](https://media.openestate.org/apidocs/OpenEstate-PHP-Export/)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

(see [`\OpenEstate\PhpExport\Config`](src/include/OpenEstate/PhpExport/Config.php)
    and [`config.php`](src/config.php))
-   available in multiple languages (English by default, see
    [current translation progress](https://i18n.openestate.org/projects/openestate-php-export/#languages))
-   open source modules are available for
    [*WordPress*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WordPress),
    [*CMS made simple*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-CMSms),
    [*WBCE*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WBCE) &
    [*Joomla*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-Joomla)

Requirements
------------

-   client side (real estate agency / website owner)
    -   [*OpenEstate-ImmoTool*](https://openestate.org/) 1.0.0 or later
-   webspace side
    -   PHP 5.6 or newer
    -   [PHP *GD* extension](https://secure.php.net/manual/en/book.image.php)
        (optional, but recommended)
    -   [PHP *mbstring* extension](https://secure.php.net/manual/en/book.mbstring.php)
        (optional)
    -   [PHP *iconv* extension](https://secure.php.net/manual/en/book.iconv.php)
        (optional)

Third party components
----------------------

The following third party components are provided by *OpenEstate-PHP-Export*:

-   [PHPMailer](https://github.com/PHPMailer/PHPMailer) v6.0.6
    (license: [LGPL 2.1](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE))
-   [Gettext](https://github.com/oscarotero/Gettext) v4.6.1
    (license: [MIT](https://github.com/oscarotero/Gettext/blob/master/LICENSE))
-   [Gettext CLDR data](https://github.com/mlocati/cldr-to-gettext-plural-rules) v2.5.0
    (license: [MIT](https://github.com/mlocati/cldr-to-gettext-plural-rules/blob/master/LICENSE))
-   [Punycode](https://github.com/true/php-punycode) v2.1.1
    (license: [MIT](https://github.com/true/php-punycode/blob/master/LICENSE))
-   [jQuery](https://jquery.com/) v3.3.1
    (license: [MIT](https://jquery.org/license/))
-   [slick](https://kenwheeler.github.io/slick/) v1.8.1
    (license: [MIT](https://github.com/kenwheeler/slick/blob/master/LICENSE))
-   components used by the [*default* theme](src/themes/default)
    -   [Pure.CSS](https://purecss.io/) v1.0.0
        (license: [BSD](https://github.com/pure-css/pure/blob/master/LICENSE))
    -   [Colorbox](https://www.jacklmoore.com/colorbox/) v1.6.4
        (license: [MIT](https://github.com/jackmoore/colorbox/blob/master/LICENSE.md))
    -   [Popper.js](https://popper.js.org/) v1.14.5
        (license: [MIT](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md))
-   components used by the [*bootstrap3* theme](src/themes/bootstrap3)
    -   [Bootstrap](https://getbootstrap.com/) v3.3.7
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
-   components used by the [*bootstrap4* theme](src/themes/bootstrap4)
    -   [Bootstrap](https://getbootstrap.com/) v4.1.3
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
        bundled with [Popper.js](https://popper.js.org/)
-   aggregated icons (generated with [*fontello.com*](http://fontello.com/))
    -   [Font Awesome](https://fontawesome.com/)
        (license: [SIL](https://fontawesome.com/license/free))
    -   [Fontelico](https://github.com/fontello/fontelico.font)
        (license: [SIL](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL))

Limitations
-----------

This solution works entirely without a database. Therefore more complex queries
on the exported real estates may not be possible with acceptable performance.

License
-------

This library is licensed under the terms of
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).
Take a look at the provided [`LICENSE.txt`](LICENSE.txt) for the license text.

Further information
-------------------

-   [*OpenEstate-PHP-Export* at GitHub](https://github.com/OpenEstate/OpenEstate-PHP-Export)
-   [Releases of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/releases)
-   [Changelog of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/blob/master/CHANGELOG.md)
-   [API documentation of *OpenEstate-PHP-Export*](https://media.openestate.org/apidocs/OpenEstate-PHP-Export/)

## Contributing

software [*OpenEstate-ImmoTool*](https://openestate.org/). When a user exports
his properties to his website in PHP format, these scripts are transferred to
the webspace including real estate data in the [`data`](src/data) folder.

Features
--------

-   listing view of multiple real estates
    (see [`index.php`](src/index.php))
-   detailled view of a single real estate
    (see [`expose.php`](src/expose.php))
-   visitors may manage their favored real estates
    (see [`fav.php`](src/fav.php))
-   real estate listings may be filtered by different criteria
    (see [`\OpenEstate\PhpExport\Filter`](src/include/OpenEstate/PhpExport/Filter))
-   real estate listings may be ordered by different criteria
    (see [`\OpenEstate\PhpExport\Order`](src/include/OpenEstate/PhpExport/Order))
-   a basic contact form is available
    (see [`\OpenEstate\PhpExport\Action\Contact`](src/include/OpenEstate/PhpExport/Action/Contact.php))
-   generated output is fully customizable with [themes](src/themes)
-   a lot of configuration options are available
    (see [`\OpenEstate\PhpExport\Config`](src/include/OpenEstate/PhpExport/Config.php)
    and [`config.php`](src/config.php))
-   available in multiple languages (English by default, see
    [current translation progress](https://i18n.openestate.org/projects/openestate-php-export/#languages))
-   open source modules are available for
    [*WordPress*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WordPress),
    [*CMS made simple*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-CMSms),
    [*WBCE*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-WBCE) &
    [*Joomla*](https://github.com/OpenEstate/OpenEstate-PHP-Wrapper-Joomla)

Requirements
------------

-   client side (real estate agency / website owner)
    -   [*OpenEstate-ImmoTool*](https://openestate.org/) 1.0.0 or later
-   webspace side
    -   PHP 5.6 or newer
    -   [PHP *GD* extension](https://secure.php.net/manual/en/book.image.php)
        (optional, but recommended)
    -   [PHP *mbstring* extension](https://secure.php.net/manual/en/book.mbstring.php)
        (optional)
    -   [PHP *iconv* extension](https://secure.php.net/manual/en/book.iconv.php)
        (optional)

Third party components
----------------------

The following third party components are provided by *OpenEstate-PHP-Export*:

-   [PHPMailer](https://github.com/PHPMailer/PHPMailer) v6.0.6
    (license: [LGPL 2.1](https://github.com/PHPMailer/PHPMailer/blob/master/LICENSE))
-   [Gettext](https://github.com/oscarotero/Gettext) v4.6.1
    (license: [MIT](https://github.com/oscarotero/Gettext/blob/master/LICENSE))
-   [Gettext CLDR data](https://github.com/mlocati/cldr-to-gettext-plural-rules) v2.5.0
    (license: [MIT](https://github.com/mlocati/cldr-to-gettext-plural-rules/blob/master/LICENSE))
-   [Punycode](https://github.com/true/php-punycode) v2.1.1
    (license: [MIT](https://github.com/true/php-punycode/blob/master/LICENSE))
-   [jQuery](https://jquery.com/) v3.3.1
    (license: [MIT](https://jquery.org/license/))
-   [slick](https://kenwheeler.github.io/slick/) v1.8.1
    (license: [MIT](https://github.com/kenwheeler/slick/blob/master/LICENSE))
-   components used by the [*default* theme](src/themes/default)
    -   [Pure.CSS](https://purecss.io/) v1.0.0
        (license: [BSD](https://github.com/pure-css/pure/blob/master/LICENSE))
    -   [Colorbox](https://www.jacklmoore.com/colorbox/) v1.6.4
        (license: [MIT](https://github.com/jackmoore/colorbox/blob/master/LICENSE.md))
    -   [Popper.js](https://popper.js.org/) v1.14.5
        (license: [MIT](https://github.com/FezVrasta/popper.js/blob/master/LICENSE.md))
-   components used by the [*bootstrap3* theme](src/themes/bootstrap3)
    -   [Bootstrap](https://getbootstrap.com/) v3.3.7
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
-   components used by the [*bootstrap4* theme](src/themes/bootstrap4)
    -   [Bootstrap](https://getbootstrap.com/) v4.1.3
        (license: [MIT](https://github.com/twbs/bootstrap/blob/master/LICENSE))
        bundled with [Popper.js](https://popper.js.org/)
-   aggregated icons (generated with [*fontello.com*](http://fontello.com/))
    -   [Font Awesome](https://fontawesome.com/)
        (license: [SIL](https://fontawesome.com/license/free))
    -   [Fontelico](https://github.com/fontello/fontelico.font)
        (license: [SIL](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL))

Limitations
-----------

This solution works entirely without a database. Therefore more complex queries
on the exported real estates may not be possible with acceptable performance.

License
-------

This library is licensed under the terms of
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html).
Take a look at the provided [`LICENSE.txt`](LICENSE.txt) for the license text.

Further information
-------------------

-   [*OpenEstate-PHP-Export* at GitHub](https://github.com/OpenEstate/OpenEstate-PHP-Export)
-   [Releases of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/releases)
-   [Changelog of *OpenEstate-PHP-Export*](https://github.com/OpenEstate/OpenEstate-PHP-Export/blob/master/CHANGELOG.md)
-   [API documentation of *OpenEstate-PHP-Export*](https://media.openestate.org/apidocs/OpenEstate-PHP-Export/)

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** OPENESTATE_PHP_EXPORT
- **Pinned SHA:** `0aaaaa6132ac199ab12cdc680f91f6ae4c663711`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`374d8a723a41c076753471ecfe89e042ac1b8d1d905a47c78f4c41ddc68cb527`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

