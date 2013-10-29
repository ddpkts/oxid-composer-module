OXID Module managed via Composer
====================

This is just a test module / skeleton to show how you can manage OXID modules via Composer.

Installation
------------

Implement module into OXID via Composer:

    {
        "repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:ddpkts/oxid-composer-module.git"
        }
        ],
        "require": {
            "ddpkts/oxid-composer-module": "dev-master"
        }
    }

Activate module in OXID backend.