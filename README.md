Presta CMS Theme Basic Bundle
=============

[![Build Status](https://secure.travis-ci.org/prestaconcept/PrestaCMSThemeBasicBundle.png)](http://travis-ci.org/prestaconcept/PrestaCMSThemeBasicBundle)
[![Total Downloads](https://poser.pugx.org/presta/cms-theme-basic-bundle/downloads.png)](https://packagist.org/packages/presta/cms-theme-basic-bundle)
[![Latest Stable Version](https://poser.pugx.org/presta/cms-theme-basic-bundle/v/stable.png)](https://packagist.org/packages/presta/cms-theme-basic-bundle)


[![SensioLabsInsight](https://insight.sensiolabs.com/projects/56721a5e-dca2-431f-bd1a-df53eca583d6/big.png)](https://insight.sensiolabs.com/projects/56721a5e-dca2-431f-bd1a-df53eca583d6)

This bundle adds basic themes to [PrestaCMS][1].

** Important ** :construction: This bundles is currently under development

:speech_balloon: If you want to have some informations about the projet progession you can register to our [google group][3]

:book: For a ready to use demonstration of PrestaCMS you should check the [prestacms-sandox available on github][2].

## Installation ##

### 1) Install dependencies

First you need to follow the [ :book: PrestaCMS installation steps][1].

### 2) Get the bundle

    php composer.phar require presta/cms-theme-basic-bundle:dev-master --no-update
    php composer.phar update presta/cms-theme-basic-bundle

### 3) Update your AppKernel to register the bundle

```php
<?php
// app/AppKernel.php
public function registerBundles()
{
    return array(
        // ...
        new Presta\CMSThemeBasicBundle\PrestaCMSThemeBasicBundle(),
        // ...
    );
}
```

## Themes

[WIP] :construction:

### Creative

![PrestaCMS Creative Theme](https://raw.github.com/prestaconcept/PrestaCMSThemeBasicBundle/master/Resources/public/theme/creative/screenshot.jpg)


## Ask for help ##

:speech_balloon: If you need help about this project you can [post a message on our google group][3]



---

*This project is supported by [PrestaConcept](http://www.prestaconcept.net)*

**Lead Developer** : @nicolas-bastien

[1]: https://github.com/prestaconcept/PrestaCMSCoreBundle
[2]: https://github.com/prestaconcept/prestacms-sandbox
[3]: https://groups.google.com/forum/?hl=fr&fromgroups#!forum/prestacms-devs
