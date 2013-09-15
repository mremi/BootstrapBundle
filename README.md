MremiBootstrapBundle
====================

[![Total Downloads](https://poser.pugx.org/mremi/bootstrap-bundle/downloads.png)](https://packagist.org/packages/mremi/bootstrap-bundle)
[![Latest Stable Version](https://poser.pugx.org/mremi/bootstrap-bundle/v/stable.png)](https://packagist.org/packages/mremi/bootstrap-bundle)

This bundle is a simple way to add the Bootstrap framework in a Symfony2
project.

## Prerequisites

This version of the bundle requires Symfony 2.3+.

## Installation

Installation is a quick 2 step process:

1. Download MremiBootstrapBundle using composer
2. Enable the Bundle

### Step 1: Download MremiBootstrapBundle using composer

Add MremiBootstrapBundle in your composer.json:

```js
{
    "require": {
        "mremi/bootstrap-bundle": "dev-master"
    }
}
```

Now tell composer to download the bundle by running the command:

``` bash
$ php composer.phar update mremi/bootstrap-bundle
```

Composer will install the bundle to your project's `vendor/mremi` directory.

### Step 2: Enable the bundle

Enable the bundle in the kernel:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Mremi\BootstrapBundle\MremiBootstrapBundle(),
    );
}
```

## Contribution

Any question or feedback? Open an issue and I will try to reply quickly.

I hope this has been useful and has helped you. If so, share it and recommend
it! :)

[@mremitsme](https://twitter.com/mremitsme)
