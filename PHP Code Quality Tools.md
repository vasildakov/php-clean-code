
# PHP Code Quality Tools

Code quality tools are software applications or libraries specifically designed to analyze, review, and assess the quality of code. These tools automate the process of code inspection, providing developers with valuable insights, recommendations, and metrics to improve the overall quality, maintainability, and efficiency of their codebase.

In PHP development, code quality tools play a crucial role in ensuring that the code adheres to established coding standards, follows best practices, and meets the requirements of a high-quality PHP application. These tools can detect various types of issues, ranging from simple syntax errors to complex architectural problems, security vulnerabilities, and performance bottlenecks.


## PHP_CodeSniffer [1]

**PHP_CodeSniffer** is a widely-used tool for enforcing coding standards in PHP. It checks the code against a set of predefined coding standards (such as PSR-12, PSR-2, and many others) and provides reports with violations and recommendations for improvement.

```sh
./vendor/bin/phpcs tests --standard=PSR12 -p
```

## PHPMD Mess Detector [2]

**PHP Mess Detector** identifies potential problems and "code smells" in PHP code. It detects complex code, unused variables, duplicated code blocks, and other issues that may indicate poor code quality. It helps developers refactor and clean up their codebase.

```sh
 ./vendor/bin/phpmd src text codesize,unusedcode,naming
```

## PHPStan [3]

**PHPStan** is a powerful static analysis tool that performs comprehensive type checking and detects potential errors in PHP code. It analyzes the codebase and provides detailed reports, highlighting type mismatches, undefined variables, and other issues.

```sh
 ./vendor/bin/phpstan analyse src tests
```

## PHPUnit [4]

**PHPUnit** is a testing framework for PHP. It enables developers to write unit tests, integration tests, and functional tests to verify the correctness of their code. It offers a wide range of assertions, test runners, and mocking capabilities.

```sh
 ./vendor/bin/phpunit .
```

## PHP_CodeCoverage [5]

**PHP_CodeCoverage** is a library that enables developers to measure the code coverage of their tests. It collects data on which parts of the code are executed during test runs, allowing developers to assess the effectiveness and completeness of their test suite.

```sh
 ./vendor/bin/phpunit --coverage-html ./build/coverage
```

## Psalm [6]

**Psalm** is a static analysis tool specifically designed for PHP. It performs advanced type inference and checks for various types of errors, including type errors, undefined variables, incorrect function calls, and more. It provides comprehensive code analysis and helps improve code quality and maintainability.

```sh
 ./vendor/bin/psalm --shepherd --stats
```


## PHPCBF PHP Code Beautifier and Fixer [7]

**PHP Code Beautifier and Fixer** is part of a set of two PHP scripts; the main phpcs script that tokenizes PHP, 
JavaScript and CSS files to detect violations of a defined coding standard, and a second phpcbf script to automatically 
correct coding standard violations. **PHP_CodeSniffer** is an essential development tool that ensures your code remains 
clean and consistent.

```sh
 ./vendor/bin/phpcbf src
```

## PHP Copy/Paste Detector (PHPCPD)
https://github.com/sebastianbergmann/phpcpd

`$ brew install phive`

`$ brew install gpg`

`$ phive install phpcpd`


PHPCPD can be used to locate duplicate code. When a project has code that has been copy+pasted there’s always a 
chance a bug will be introduced when the logic is updated in one place and not another. Using PHPCPD is a great way 
to locate logic that exists in multiple places. It can also be used to alert you that you’ve created something that 
may need to extracted into a new component.

`php ./vendor/bin/phpcpd src`


## PHP Lines of Code (PHPLOC)
https://github.com/sebastianbergmann/phploc

PHPLOC is a great way to quickly measure the overall size of a project. It’s very useful for getting a handle on the 
issues that an existing project may face.
`php ./vendor/bin/phploc src`


## Code Review and Analysis:
Code review is the process of examining code to identify errors, improve quality, and ensure adherence to coding standards. Code analysis on the other hand is the automated examination of code using specialized tools to detect syntax errors, coding style violations, unused variables, code complexity, and security vulnerabilities.

## Integrating Code Quality Tools into the Workflow

Integrating PHP code quality tools into development workflow is essential for successful project delivery. It helps to maintain high standards of code quality, regularly running code analysis, addressing reported issues, and iterating on the codebase based on the tool's feedback.
Let's look as some key things to consider for incorporating these tools effectively.

[1]: https://github.com/squizlabs/PHP_CodeSniffer "PHP_CodeSniffer"
[2]: https://phpmd.org/ "PHPMD Mess Detector"
[3]: https://phpstan.org/ "PHPStan"
[4]: https://phpunit.de/ "PHPUnit"
[5]: https://github.com/sebastianbergmann/php-code-coverage "PHP_CodeCoverage"
[6]: https://psalm.dev/ "Psalm"
[7]: https://pear.php.net/package/PHP_CodeSniffer "PHPCBF"
[8]: https://dev.to/documatic/top-6-php-code-quality-tools-2023-2kb1 "Top 6 PHP code quality tools 2023"