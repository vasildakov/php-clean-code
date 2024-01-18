## Composer

Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on 
and it will manage (install/update) them for you.

---

## Phive

Phive is a PHP tool, that can be used to install, update, and validate Phar archives easily. Phive saves the hassle 
of finding the Phar file URLs, downloading them, changing their permissions, and making them to ready to use within 
the applications.

Further, Phive validates the GPG signatures of Phar archives by default. This avoids supply-chain attacks, and makes 
it very convenient to do so. Let's be real - it is very unlikely that one would lookup the authors GPG keys, download 
them off a keyserver, and manually validate their signatures. Phive does this by default for all supported Phar 
archives.

Phive also provides support a custom phive.xml configuration file to declare the Phive files and their version 
constraints. With a phive.xml file, it is easy to share the tooling setup of any PHP application with others.

Developed by Arne Blankerts, Sebastian Heuer, and dozens of other brilliant minds, Phive can help in development 
environments, CI/CD setups, etc. to quickly setup all the tools required for a PHP project.

---

## Phive vs Composer

Composer and Phive are similar in the sense that they both are dependency managers.

Composer provides autoloading capabilities, custom repositories, and more features. Phive, on the other hand, has a 
very focused use-case. It is meant to be used as a tool to download and install other Phar archives. It supports 
installing Phar extensions from an arbitrary URL, but its usual use case installing a smaller set well-known and 
aliased PHP tools such as PHPUnit, PHPLoC, PHP CS Fixer, etc.

Unlike Composer, Phive provides built-in GPG integration to validate the signature of the Phars being downloaded. 
Composer can validate Composer itself during an upgrade, but it does not validate the downloaded packages against the 
authors known GPG keys.

Phive can be used alongside Composer, that dependencies set in the composer.json can be moved to a new phive.xml 
configuration file. This can reduce potential dependency conflicts at Composer installations.

---

## PECL

PECL is a repository for PHP Extensions, providing a directory of all known extensions and hosting facilities for 
downloading and development of PHP extensions. The packaging and distribution system used by PECL is shared with its 
sister, PEAR.

---

## PEAR

PEAR is short for "PHP Extension and Application Repository" and is pronounced just like the fruit. The purpose of 
PEAR is to provide:

- A structured library of open-source code for PHP users
- A system for code distribution and package maintenance
- A standard style for code written in PHP, specified here
- The PHP Extension Community Library (PECL), see more below
- A web site, mailing lists and download mirrors to support the PHP/PEAR community

PEAR is a community-driven project governed by its developers. PEAR's governing bodies are subdivided into the PEAR Group, Collectives, and a President. PEAR's constitution (adopted in March 2007) defining these groups is documented here. The PEAR project was founded in 1999 by Stig S. Bakken and quite a lot of people have joined the project.

---

## Phar

Phar (short for PHP Archive) is a library that enables developers to package an entire PHP application into a single 
file, called a Phar archive. The Phar archive can include PHP files, images, JavaScript, CSS, and other assets required 
for your application to run. The main advantage of using Phar archives is that it simplifies the process of deploying 
and distributing PHP applications, as users only need to download a single file to use your application.

---

## PHP Extensions
PHP extensions are a critical part of the PHP development process, extending the functionality of the language to meet 
the needs of many different types of applications. 

PHP extensions are usually written in C and then compiled to native machine code. However, PHP 7.4 introduced 
Foreign Function Interface (PHP FFI), which enables PHP developers to write extensions and bindings to C libraries in 
pure PHP.

### Sodium
Sodium is a modern, easy-to-use software library for encryption, decryption, signatures, password hashing and more. 
Its goal is to provide all of the core operations needed to build higher-level cryptographic tools.

### Xdebug
Xdebug is an extension for PHP, and provides a range of features to improve the PHP development experience.

### PCOV
PCOV is a PHP driver used in PHPUnit for code coverage, similar to Xdebug or PHPDBG. It can be used to collect 
information about code coverage lines during testing.



### PHP Extensions That Come With PHP

### Third-Party PHP Extensions

### Links
- [php-development-using-php-extensions](https://www.zend.com/blog/php-development-using-php-extensions)
- [most-useful-php-extensions](https://hostry.com/blog/top-most-useful-php-extensions/?d=1)
- [phpunit-code-coverage-pcov](https://geshan.com.np/blog/2020/11/phpunit-code-coverage-pcov/)
- [quickly-switching-between-pcov-and-xdebug](https://localheinz.com/articles/2020/05/16/quickly-switching-between-pcov-and-xdebug/)
- [php-extensions](https://docs.php.earth/docker/php-extensions/)



---

## Links

https://php.watch/articles/phive
https://reintech.io/blog/beginners-guide-php-phar-library-packaging-distribution


