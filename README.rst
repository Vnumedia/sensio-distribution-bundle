SensioDistributionBundle
========================

**WARNING**: This bundle does not support Symfony 4. Symfony Flex is a total replacement for this bundle.

SensioDistributionBundle provides useful developer features that can be re-used
amongst several Symfony Distributions.

Composer Hooks
--------------

The bundle hooks up into the Composer process to automate the following actions
when running an install or an update:

* Update the ``bootstrap.php.cache`` file (and clears the cache);

* Install the assets under the web root directory;

* Update the requirements file.

Contributing
------------

To contribute to this bundle, you just need a GitHub account.
If you need some help to start, you can check the `Symfony guidelines`_ and `code style conventions`_.
Bug fixes should be submitted against the 4.0 branch when possible, and new features are accepted on master only.

Pull requests are welcome!

.. _Symfony guidelines: https://symfony.com/doc/current/contributing/code/patches.html
.. _code style conventions: https://symfony.com/doc/current/contributing/code/standards.html
