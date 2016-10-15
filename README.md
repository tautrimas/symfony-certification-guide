Symfony 3 certification guide
===========================

This is not an official guide, it's only a compilation of links extracted from the documentation based on the [Symfony Certification](http://sensiolabs.com/en/symfony/certification.html) page topics.

Even if you have no plans to take the Symfony certification exam, this list of resources may help you better understand the Symfony framework.

Feel free to fork and send a PR.

### **Topics**
---
#### **PHP**
* Object Oriented Programming  
http://www.php.net/manual/en/oop5.intro.php
* Namespaces  
http://www.php.net/manual/en/language.namespaces.php  
https://knpuniversity.com/screencast/php-namespaces-in-120-seconds/namespaces  
* Interfaces  
http://www.php.net/manual/en/language.oop5.interfaces.php
* Anonymous functions and closures  
http://www.php.net/manual/en/functions.anonymous.php
* Abstract classes  
http://www.php.net/manual/en/language.oop5.abstract.php
* Exception and error handling
* Traits
http://php.net/manual/en/language.oop5.traits.php
* PHP extensions
* SPL
http://php.net/manual/en/book.spl.php
* Web security (XSS, CSRF, etc.)
http://php.net/manual/en/security.php

---

#### **HTTP**
* Client / Server interaction  
http://symfony.com/doc/3.0/book/http_fundamentals.html
* Status codes  
http://en.wikipedia.org/wiki/List_of_HTTP_status_codes
* HTTP request  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#request
* HTTP response  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#response

* RFC 2616
http://www.ietf.org/rfc/rfc2616.txt
* HTTP methods
* Cookies
* Caching
* Content negotiation
* Language detection

---

#### **Symfony Architecture**
* Standard edition of Symfony
http://symfony.com/distributions
* Components  
http://symfony.com/doc/3.0/components/index.html
* Bundles  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html
http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-bundle-system
* Bridges  
http://stackoverflow.com/questions/11888522/what-are-symfony-bridges-bundles-and-vendor?answertab=votes#tab-top
*  Configuration  
http://symfony.com/doc/3.0/quick_tour/the_architecture.html#configuring-a-bundle  
http://symfony.com/doc/3.0/cookbook/configuration/index.html
http://symfony.com/doc/3.0/components/config/index.html
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#configuration  
http://symfony.com/doc/3.0/cookbook/bundles/extension.html  
*  Code organization  
http://symfony.com/doc/3.0/quick_tour/the_architecture.html#understanding-the-directory-structure
* Request handling  
http://symfony.com/doc/3.0/book/http_fundamentals.html#the-journey-from-the-request-to-the-response
* Exception handling
http://symfony.com/doc/3.0/controller/error_pages.html
* Event dispatcher and kernel events
http://symfony.com/doc/3.0/components/event_dispatcher.html
http://symfony.com/doc/3.0/reference/events.html#kernel-events
* Official best practices
http://symfony.com/doc/3.0/best_practices/index.html
* Release management
http://symfony.com/doc/3.0/contributing/community/releases.html
* Backward compatibility promise
http://symfony.com/doc/3.0/contributing/community/releases.html#backwards-compatibility
* Deprecations best practices
http://symfony.com/doc/3.0/contributing/community/releases.html#deprecations
http://symfony.com/doc/3.0/contributing/code/conventions.html#contributing-code-conventions-deprecations

---

#### **Standardisation**
* Naming conventions  
http://symfony.com/doc/3.0/contributing/code/standards.html#naming-conventions
* Coding standards  
http://symfony.com/doc/3.0/contributing/code/standards.html
* Integration of third-party libraries  
http://symfony.com/doc/3.0/cookbook/bundles/installation.html
* Composer packages handling  
http://symfony.com/doc/3.0/book/installation.html
https://knpuniversity.com/screencast/composer
* Development best practices
http://symfony.com/doc/3.0/best_practices/index.html
* Override the framework  
http://symfony.com/doc/3.0/cookbook/bundles/override.html
* Semantic versioning
http://semver.org/

---

#### **Bundles**
* Naming conventions  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#bundle-name
* Code organization  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#directory-structure
* The controllers  
http://symfony.com/doc/3.0/cookbook/bundles/best_practices.html#controllers
http://symfony.com/doc/3.0/cookbook/controller/index.html
http://symfony.com/doc/3.0/book/controller.html
* The views  
http://symfony.com/doc/3.0/quick_tour/the_view.html
* The resources
* Overriding default error pages
* http://symfony.com/doc/3.0/controller/error_pages.html
* Bundle inheritance
* http://symfony.com/doc/3.0/bundles/inheritance.html
* http://symfony.com/doc/3.0/bundles/override.html
* Event dispatcher and kernel events
* Semantic configuration and compiler passes
http://symfony.com/doc/3.0/service_container/compiler_passes.html

---

#### **The controllers**
* Naming conventions  
http://symfony.com/doc/3.0/book/routing.html#controller-string-syntax
* Get the request  
http://symfony.com/doc/3.0/book/controller.html#requests-controller-response-lifecycle
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#request
* Generate the response  
http://symfony.com/doc/3.0/book/controller.html#requests-controller-response-lifecycle
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#response
* The cookies  
http://symfony.com/doc/3.0/components/http_foundation/introduction.html#setting-cookies
* The session  
http://symfony.com/doc/3.0/book/controller.html#managing-the-session
http://symfony.com/doc/3.0/components/http_foundation/sessions.html
* Session flashbag  
http://symfony.com/doc/3.0/book/controller.html#flash-messages
http://symfony.com/doc/3.0/components/http_foundation/sessions.html#flash-messages
* Redirects  
http://symfony.com/doc/3.0/book/controller.html#redirecting
* Internal redirects  
http://symfony.com/doc/3.0/book/controller.html#forwarding-to-another-controller
* Generate 404 pages  
http://symfony.com/doc/3.0/book/controller.html#managing-errors-and-404-pages
http://symfony.com/doc/3.0/cookbook/controller/error_pages.html#customizing-the-404-page-and-other-error-pages
* File upload
http://symfony.com/doc/3.0/controller/upload_file.html
* Built-in internal controllers
---

#### **The Routing**
* Configuration (YAML / XML / PHP & annotations)  
http://symfony.com/doc/3.0/book/routing.html#basic-route-configuration
* Restrict URL parameters  
http://symfony.com/doc/3.0/book/routing.html#routing-with-placeholders
* Set default values to URL parameters  
http://symfony.com/doc/3.0/book/routing.html#required-and-optional-placeholders
* Generate URL parameters  
http://symfony.com/doc/3.0/book/routing.html#generating-urls
http://symfony.com/doc/3.0/book/routing.html#generating-urls-with-query-strings
* Trigger redirections  
http://symfony.com/doc/master/cmf/components/routing/dynamic.html#redirections
http://symfony.com/doc/3.0/cookbook/routing/redirect_in_config.html
* Special internal routing attributes
* Domain name matching
http://symfony.com/doc/3.0/routing/hostname_pattern.html
* Conditional request matching
http://symfony.com/doc/3.0/routing/conditions.html
* HTTP methods matching
http://symfony.com/doc/3.0/routing/requirements.html#adding-http-method-requirements
* User's locale guessing
http://symfony.com/doc/3.0/translation/locale.html
* Router debugging
http://symfony.com/doc/3.0/routing/debug.html

---

#### **Templating with Twig**
* Auto escape  
http://twig.sensiolabs.org/doc/tags/autoescape.html
http://symfony.com/doc/3.0/book/templating.html#output-escaping-in-twig
* Template inheritance  
http://twig.sensiolabs.org/doc/tags/extends.html
http://twig.sensiolabs.org/doc/templates.html#template-inheritance
http://symfony.com/doc/3.0/book/templating.html#template-inheritance-and-layouts
* Global functions  
http://twig.sensiolabs.org/doc/functions/index.html
* Filters  
http://twig.sensiolabs.org/doc/filters/index.html
* Template includes  
http://twig.sensiolabs.org/doc/tags/include.html
* Control statements (loops and conditions)  
http://twig.sensiolabs.org/doc/tags/for.html
http://twig.sensiolabs.org/doc/templates.html#control-structure
* Urls generation  
http://symfony.com/doc/3.0/book/routing.html#generating-urls-from-a-template
http://symfony.com/doc/3.0/book/templating.html#linking-to-pages
* Call a controller from a view  
http://symfony.com/doc/3.0/book/templating.html#embedding-controllers
* Translations  
http://symfony.com/doc/3.0/book/translation.html#translations-in-templates
* String interpolation
http://twig.sensiolabs.org/doc/templates.html#string-interpolation
* Assets management
* Debugging variables
http://symfony.com/doc/3.0/templating/debug.html
http://twig.sensiolabs.org/doc/functions/dump.html

---

#### **Forms**
* Create forms  
http://symfony.com/doc/3.0/book/forms.html#creating-a-simple-form
* Handling forms  
http://symfony.com/doc/3.0/book/forms.html#handling-form-submissions
* Form types  
http://symfony.com/doc/3.0/book/forms.html#creating-form-classes
http://symfony.com/doc/3.0/book/forms.html#built-in-field-types
* Render forms with Twig  
http://symfony.com/doc/3.0/book/forms.html#rendering-a-form-in-a-template
* Forms security (CSRF)  
http://symfony.com/doc/3.0/book/forms.html#csrf-protection
* Forms theming
http://symfony.com/doc/3.0/form/form_themes.html
* Handling file upload
* Built-in form types
* Data transformers
* Form events
* Form type extensions

---

#### **Validation**
* Validate a PHP object  
http://symfony.com/doc/3.0/book/validation.html#the-basics-of-validation
* Native validation rules  
http://symfony.com/doc/3.0/book/validation.html#constraints
* Validation scopes  
* Validation groups  
http://symfony.com/doc/3.0/book/validation.html#validation-groups
* Group sequence
* Custom callback validators
* Violations builder

---

#### **Dependency Injection**
* The Service container  
http://symfony.com/doc/3.0/book/service_container.html
* Global configuration parameters
http://symfony.com/doc/3.0/components/dependency_injection/parameters.html
http://symfony.com/doc/3.0/components/dependency_injection/introduction.html#setting-up-the-container-with-configuration-files
* Symfony2 services  
http://symfony.com/doc/3.0/book/service_container.html#what-is-a-service
* Register new services  
http://symfony.com/doc/3.0/book/service_container.html#creating-configuring-services-in-the-container
* Tags  
http://symfony.com/doc/3.0/book/service_container.html#tags
http://symfony.com/doc/3.0/reference/dic_tags.html
* Semantic configuration  
http://symfony.com/doc/3.0/cookbook/bundles/extension.html
* Factories
* Compiler passes
* Services autowiring

---

#### **Security**
* Authentication  
http://symfony.com/doc/3.0/components/security/authentication.html
http://symfony.com/doc/3.0/book/security.html#how-security-works-authentication-and-authorization
* Authorization  
http://symfony.com/doc/3.0/components/security/authorization.html
http://symfony.com/doc/3.0/book/security.html#authorization
* Configuration  
http://symfony.com/doc/3.0/reference/configuration/security.html
* Providers  
http://symfony.com/doc/3.0/book/security.html#where-do-users-come-from-user-providers
* Firewalls  
http://symfony.com/doc/3.0/book/security.html#firewalls-authentication
http://symfony.com/doc/3.0/components/security/firewall.html
* Users  
http://symfony.com/doc/3.0/book/security.html#users
* Encoders  
http://symfony.com/doc/3.0/book/security.html#encoding-the-user-s-password
* Roles  
http://symfony.com/doc/3.0/components/security/authorization.html#roles
http://symfony.com/doc/3.0/book/security.html#roles
* Access Control Rules  
http://symfony.com/doc/3.0/book/security.html#access-control-in-templates
http://symfony.com/doc/3.0/book/security.html#access-control-in-controllers
* Guard authenticators
* Voters and voting strategies

---

#### **HTTP Cache**
* Cache types (browser, proxies and reverse proxies)  
http://symfony.com/doc/3.0/book/http_cache.html#types-of-caches
* Expiration (Expires, Cache-control)  
http://symfony.com/doc/3.0/book/http_cache.html#expiration
* Validation (ETag, Last-Modified)  
http://symfony.com/doc/3.0/book/http_cache.html#validation
* Client cache  
* Server cache  
* Edge Side Includes  
http://symfony.com/doc/3.0/book/http_cache.html#using-edge-side-includes

---

#### **The command line**
* Symfony2 commands  
http://symfony.com/doc/3.0/components/console/usage.html#built-in-commands
* Custom commands  
http://symfony.com/doc/3.0/components/console/introduction.html#creating-a-basic-command  
http://symfony.com/doc/3.0/cookbook/console/console_command.html
* Configuration  
* Options and arguments  
http://symfony.com/doc/3.0/components/console/introduction.html#using-command-options  
http://symfony.com/doc/3.0/components/console/introduction.html#using-command-arguments
* Input and Output objects
* Built-in helpers
* Console events
* Verbosity levels

---

#### **Automated tests**
* Unit tests with PHPUnit  
http://symfony.com/doc/3.0/book/testing.html#the-phpunit-testing-framework
* Functional tests  
http://symfony.com/doc/3.0/book/testing.html#functional-tests
* The Client object  
http://symfony.com/doc/3.0/book/testing.html#working-with-the-test-client
* The Crawler object  
http://symfony.com/doc/3.0/book/testing.html#the-crawler
* The Profile object  
http://symfony.com/doc/3.0/book/testing.html#accessing-the-profiler-data
http://symfony.com/doc/3.0/cookbook/testing/profiling.html
* Access framework objects  
http://symfony.com/doc/3.0/book/testing.html#accessing-internal-objects
http://symfony.com/doc/3.0/book/testing.html#accessing-the-container
* Configure the client  
* Request and response objects introspection  
http://symfony.com/doc/3.0/book/testing.html#accessing-internal-objects
* PHPUnit bridge
* Handling legacy deprecated code

---

#### **Miscellaneous**
* Error handling  
http://symfony.com/doc/3.0/cookbook/controller/error_pages.html
* Debug the code  
http://symfony.com/doc/3.0/cookbook/debugging.html
* Deployment best practices
* Process
* Data collectors
* Web Profiler and Web Debug Toolbar
* Internationalization and localization

### **Resources**
---
#### **Documentation**
* The Symfony Book  
http://symfony.com/doc/3.0/book/index.html
* The Symfony Cookbook  
http://symfony.com/doc/3.0/cookbook/index.html
* The Symfony Book Spanish  
http://librosweb.es/symfony_2_3/  
The Symfony Glossary  
http://symfony.com/doc/3.0/glossary.html

---

#### **Books**
* Desarrollo web ágil con Symfony2 Spanish  
http://symfony.es/libro/  
* A year with Symfony  
https://leanpub.com/a-year-with-symfony  
* Un año con Symfony Spanish  
https://leanpub.com/un-ano-con-symfony  
* Extending Symfony2 Web Application Framework  
http://www.packtpub.com/extending-symfony-2-web-application-framework/book  
* Testing para Aplicaciones Symfony2 Spanish  
https://leanpub.com/testingsymfony2  
* Symfony Enterprise Applications
https://leanpub.com/symfony-enterprise-applications
* Extending Symfony2 Web Application Framework
https://www.packtpub.com/web-development/extending-symfony2-web-application-framework
* Symfony Certification. Unofficial self-study guide  
https://leanpub.com/symfony-selfstudy

---

#### **Other**
* KNP University - PHP and Symfony Tutorial Screencasts  
http://knpuniversity.com/
* SymfonyBricks  
https://symfonybricks.com/
* Symfony2 cheat sheet  
http://www.symfony2cheatsheet.com/
* Symfony2 Tutorials  
http://www.screenfony.com/
* Symfony2 deployment checklist  
http://www.symfony2-checklist.com/
* A Symfony Console CLI tool to train on Symfony certification  
https://github.com/certificationy/certificationy-cli  
* A Symfony Web Platform tool to train on Symfony certification  
http://www.certificationy.com/
