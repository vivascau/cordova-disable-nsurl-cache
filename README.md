Cordova Disable NSURL Cache
===========

Cordova plugin which completely disables the NSURL cache.

Maintainer: Mauro Gadaleta <<mauro.gadaleta@wonga.com>>


Installation
------------

Cordova:

```sh
cordova plugin add https://github.com/wongatech/cordova-disable-nsurl-cache.git
```

Usage
-----

Add the onload flag to true in your config plugin file

```xml
<feature name="CordovaDisableNSURLCache">
    <param name="ios-package" value="CordovaDisableNSURLCache" onload="true"/>
</feature>
```


Contributing
------------

We :heart: pull requests!

To contribute:

- Fork the repo
- Update README.md and, if necessary, the demo page
