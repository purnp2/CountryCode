CountryCode
===========

Note
----
This repository is an improved version of [TakahikoKawasaki/CountryCode](https://github.com/TakahikoKawasaki/CountryCode). However, that repository is acknowledged to be deprecated and replaced by its original author and moved to [nv-i18n](https://github.com/TakahikoKawasaki/nv-i18n).
See https://github.com/TakahikoKawasaki/nv-i18n

Overview
--------

ISO 3166-1 (alpha-2/alpha-3/numeric) country code enum in Java.

License
-------

Apache License, Version 2.0

Download
--------

    git clone git://github.com/TakahikoKawasaki/CountryCode.git

Javadoc
-------

[CountryCode Javadoc](http://takahikokawasaki.github.com/CountryCode/index.html)

Example
-------

    CountryCode cc = CountryCode.getByCode("JP");

    System.out.println("Country name = " + cc.getName());                  // "Japan"
    System.out.println("ISO 3166-1 alpha-2 code = " + cc.getAlpha2());     // "JP"
    System.out.println("ISO 3166-1 alpha-3 code = " + cc.getAlpha3());     // "JPN"
    System.out.println("ISO 3166-1 numeric code = " + cc.getNumeric());    // 392

See Also
--------

* [ISO 3166-1](http://en.wikipedia.org/wiki/ISO_3166-1)
* [ISO 3166-1 alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)
* [ISO 3166-1 alpha-3](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-3)
* [ISO 3166-1 numeric](http://en.wikipedia.org/wiki/ISO_3166-1_numeric)

Author
------

Takahiko Kawasaki, Neo Visionaries Inc.
