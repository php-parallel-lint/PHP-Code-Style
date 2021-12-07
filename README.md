PHP Code Style
=================

Basic, PSR-12 based, coding standard for use by projects in the PHP Parallel Lint GitHub organisation.

## Installation

Install this standard via Composer:

```bash
composer require --dev php-parallel-lint/php-code-style
```

## Using the standard

Once installed for a project, use this standard via the command-line:
```bash
vendor/bin/phpcs . --standard=PHPParallelLint
```

Or use the standard in a project specific PHPCS ruleset:
```xml
<?xml version="1.0"?>
<ruleset name="Project Name">

    <rule ref="PHPParallelLint"/>

</ruleset>
```
