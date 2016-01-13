# ModeraUpgradeBundle

[![Build Status](https://travis-ci.org/modera/ModeraUpgradeBundle.svg?branch=master)](https://travis-ci.org/modera/ModeraUpgradeBundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/modera/ModeraUpgradeBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/modera/ModeraUpgradeBundle/?branch=master)
[![StyleCI](https://styleci.io/repos/29133176/shield)](https://styleci.io/repos/29133176)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/e0f6dba2-92a4-4be3-a311-c5e2c1226caf/mini.png)](https://insight.sensiolabs.com/projects/e0f6dba2-92a4-4be3-a311-c5e2c1226caf)

## Installation

### Step 1: update your vendors by running

    $ php composer.phar require modera/upgrade-bundle:dev-master

### Step2: Enable the bundle

    <?php
    // app/AppKernel.php

    public function registerBundles()
    {
        $bundles = array(
            // ...

            new Modera\UpgradeBundle\ModeraUpgradeBundle(),
        );
    }

### Step3: Update dependencies in "composer.json"

    $ php app/console modera:upgrade --dependencies

## Licensing

This bundle is under the MIT license. See the complete license in the bundle:
Resources/meta/LICENSE
