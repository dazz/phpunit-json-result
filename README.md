# PHPUnit Json Result Printer

Other PHP CLI tool can communicate with API using JSON. Why not PHPUnit?

This package requires PHPUnit 11.5.51+ and PHP 8.1+.

<br>

## Install

```bash
composer require --dev tomasvotruba/phpunit-json-result-printer
```

## Usage

Register extension in your `phpunit.xml` file:

```xml
<extensions>
    <bootstrap class="TomasVotruba\PHPUnitJsonResultPrinter\PHPUnitJsonResultPrinterExtension" />
</extensions>
```
