# Contributions are welcome!

## Quick guide

 * Fork the repo.
 * Checkout the branch you want to make changes on.
 * Install dependencies: `composer install`.
 * Create branch, e.g. `feature-foo` or `bugfix-bar`.
 * Make changes.
 * If you are adding functionality or fixing a bug - add a test!
 * Check if tests pass: `phpunit` [(4.*)](https://phpunit.de/manual/current/en/installation.html)

## Opening a pull request

You can do some things to increase the chance that your pull request is accepted the first time:

 * Submit one pull request per fix or feature.
 * If your changes are not up to date - rebase your branch on master.
 * Follow the conventions used in the project.
 * Remember about tests and documentation.
 * Don't bump version.

## Project's standards

 * [PSR-0: Autoloading Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)
 * [PSR-1: Basic Coding Standard](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
 * [PSR-2: Coding Style Guide](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)
 * [Symfony Coding Standards](http://symfony.com/doc/current/contributing/code/standards.html)
 * Keep the order of class elements: static properties, instance properties, constructor 
    (or setUp for PHPUnit), destructor (or tearDown for PHPUnit), static methods, instance methods, magic static methods, magic instance methods.
