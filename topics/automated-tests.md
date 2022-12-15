---
title: Automated Tests - Symfony Certification Preparation List
---
[Back to index](../readme.md#table-of-contents)

# Automated Tests
 - [ ] [Testing](https://symfony.com/doc/6.0/testing.html)
 - [ ] [PHPUnit 9.5 Manual](https://phpunit.readthedocs.io/en/9.5/)

## Unit tests with PHPUnit
- [ ] [Unit tests - symfony.com](https://symfony.com/doc/6.0/testing.html#unit-tests)
- [ ] [Writing Tests for PHPUnit](https://phpunit.readthedocs.io/en/9.5/writing-tests-for-phpunit.html)
    - [ ] [Test Dependencies](https://phpunit.readthedocs.io/en/9.5/writing-tests-for-phpunit.html#test-dependencies)
    - [ ] [Data Providers](https://phpunit.readthedocs.io/en/9.5/writing-tests-for-phpunit.html#data-providers)
    - [ ] [Testing Exceptions](https://phpunit.readthedocs.io/en/9.5/writing-tests-for-phpunit.html#testing-exceptions)
    - [ ] [Assertions](https://phpunit.readthedocs.io/en/9.5/assertions.html)
    - [ ] [Test Doubles](https://phpunit.readthedocs.io/en/9.5/test-doubles.html)
      - [ ] [Stub](https://phpunit.readthedocs.io/en/9.5/test-doubles.html#stubs)
      - [ ] [Mock](https://phpunit.readthedocs.io/en/9.5/test-doubles.html#mock-objects)

## Functional tests with PHPUnit
- [ ] [Functional tests - symfony.com](https://symfony.com/doc/6.0/testing.html#functional-tests)
- [ ] [Configuring a Database for Tests](https://symfony.com/doc/6.0/testing.html#configuring-a-database-for-tests)
- [ ] [Fixtures](https://phpunit.readthedocs.io/en/9.5/fixtures.html)
- [ ] [WebTestCase abstract class](https://github.com/symfony/symfony/blob/6.0/src/Symfony/Bundle/FrameworkBundle/Test/WebTestCase.php)

## Client object
- [ ] [Working with the Test Client - symfony.com](https://symfony.com/doc/6.0/testing.html#working-with-the-test-client)
- [ ] `$client = static::createClient();`
- [ ] [KernelBrowser](https://github.com/symfony/symfony/blob/6.0/src/Symfony/Bundle/FrameworkBundle/KernelBrowser.php)

## Crawler object
- [ ] [The DomCrawler Component](https://symfony.com/doc/6.0/components/dom_crawler.html)
- [ ] [The Crawler - symfony.com](https://symfony.com/doc/6.0/testing.html#the-crawler)
- [ ] `$crawler = $client->request('GET', '/');`
- [ ] [Crawler class](https://github.com/symfony/symfony/blob/6.0/src/Symfony/Component/DomCrawler/Crawler.php)

## Profiler object
- [ ] [How to Use the Profiler in a Functional Test - symfony.com](https://symfony.com/doc/6.0/testing/profiling.html)

## Framework objects access
- [ ] [Retrieving Services in the Test](https://symfony.com/doc/6.0/testing.html#retrieving-services-in-the-test)
- [ ] [Accessing the Container - symfony.com](https://symfony.com/doc/6.0/testing.html#accessing-the-container)

## Client configuration
- [ ] [Testing Configuration - symfony.com](https://symfony.com/doc/6.0/testing.html#testing-configuration)

## Request and response objects introspection
- [ ] [Accessing Internal Objects - symfony.com](https://symfony.com/doc/6.0/testing.html#accessing-internal-objects)

## PHPUnit bridge
- [ ] [The PHPUnit Bridge - symfony.com](https://symfony.com/doc/6.0/components/phpunit_bridge.html)

## Handling legacy deprecated code
- [ ] [SYMFONY_DEPRECATIONS_HELPER](https://symfony.com/doc/6.0/components/phpunit_bridge.html#configuration)
