---
title: Console - Symfony Certification Preparation List
---
[Back to index](../readme.md#table-of-contents)

# Console
- [The Console Component - symfony.com](http://symfony.com/doc/3.0/components/console.html)

## Built-in commands
- [Using Console Commands, Shortcuts and Built-in Commands - symfony.com](https://symfony.com/doc/3.0/components/console/usage.html)

Available commands on Symfony 3.0 standart edition. Same list could be seen when running `bin/console list`.

```
  help                                    Displays help for a command
  list                                    Lists commands
 assets
  assets:install                          Installs bundles web assets under a public web directory
 cache
  cache:clear                             Clears the cache
  cache:warmup                            Warms up an empty cache
 config
  config:dump-reference                   Dumps the default configuration for an extension
 debug
  debug:config                            Dumps the current configuration for an extension
  debug:container                         Displays current services for an application
  debug:event-dispatcher                  Displays configured listeners for an application
  debug:router                            Displays current routes for an application
  debug:swiftmailer                       Displays current mailers for an application
  debug:translation                       Displays translation messages information
  debug:twig                              Shows a list of twig functions, filters, globals and tests
 doctrine
  doctrine:cache:clear-collection-region  Clear a second-level cache collection region.
  doctrine:cache:clear-entity-region      Clear a second-level cache entity region.
  doctrine:cache:clear-metadata           Clears all metadata cache for an entity manager
  doctrine:cache:clear-query              Clears all query cache for an entity manager
  doctrine:cache:clear-query-region       Clear a second-level cache query region.
  doctrine:cache:clear-result             Clears result cache for an entity manager
  doctrine:database:create                Creates the configured database
  doctrine:database:drop                  Drops the configured database
  doctrine:ensure-production-settings     Verify that Doctrine is properly configured for a production environment.
  doctrine:generate:crud                  Generates a CRUD based on a Doctrine entity
  doctrine:generate:entities              Generates entity classes and method stubs from your mapping information
  doctrine:generate:entity                Generates a new Doctrine entity inside a bundle
  doctrine:generate:form                  Generates a form type class based on a Doctrine entity
  doctrine:mapping:convert                Convert mapping information between supported formats.
  doctrine:mapping:import                 Imports mapping information from an existing database
  doctrine:mapping:info
  doctrine:query:dql                      Executes arbitrary DQL directly from the command line.
  doctrine:query:sql                      Executes arbitrary SQL directly from the command line.
  doctrine:schema:create                  Executes (or dumps) the SQL needed to generate the database schema
  doctrine:schema:drop                    Executes (or dumps) the SQL needed to drop the current database schema
  doctrine:schema:update                  Executes (or dumps) the SQL needed to update the database schema to match the current mapping metadata.
  doctrine:schema:validate                Validate the mapping files.
 generate
  generate:bundle                         Generates a bundle
  generate:command                        Generates a console command
  generate:controller                     Generates a controller
  generate:doctrine:crud                  Generates a CRUD based on a Doctrine entity
  generate:doctrine:entities              Generates entity classes and method stubs from your mapping information
  generate:doctrine:entity                Generates a new Doctrine entity inside a bundle
  generate:doctrine:form                  Generates a form type class based on a Doctrine entity
 lint
  lint:twig                               Lints a template and outputs encountered errors
  lint:yaml                               Lints a file and outputs encountered errors
 orm
  orm:convert:mapping                     Convert mapping information between supported formats.
 router
  router:match                            Helps debug routes by simulating a path info match
 security
  security:check                          Checks security issues in your project dependencies
  security:encode-password                Encodes a password.
 server
  server:run                              Runs PHP built-in web server
  server:start                            Starts PHP built-in web server in the background
  server:status                           Outputs the status of the built-in web server for the given address
  server:stop                             Stops PHP's built-in web server that was started with the server:start command
 swiftmailer
  swiftmailer:debug                       Displays current mailers for an application
  swiftmailer:email:send                  Send simple email message
  swiftmailer:spool:send                  Sends emails from the spool
 translation
  translation:update                      Updates the translation file
```

## Custom commands
- [Console Commands - symfony.com](http://symfony.com/doc/3.0/console.html)

## Configuration
- [Configuring the Command - symfony.com](http://symfony.com/doc/3.0/console.html#configuring-the-command)

## Options and arguments
- [Console Input (Arguments & Options) - symfony.com](https://symfony.com/doc/3.0/console/input.html)

## Input and Output objects

## Built-in helpers
- [The Console Helpers - symfony.com](https://symfony.com/doc/3.0/components/console/helpers/index.html)

## Console events
- [Using Events - symfony.com](https://symfony.com/doc/3.0/components/console/events.html)

## Verbosity levels
- [Verbosity levels - symfony.com](https://symfony.com/doc/3.0/console/verbosity.html)
