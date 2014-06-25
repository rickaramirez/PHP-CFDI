PHP-CFDI
========

PHP Parser for CFDI XMLs

This is an early version of the PHP-CFDI please report any bug or issues.

Usage (example)
===============

require_once '../src/autoload.php';

$parser = new Parser('fullpath/file.xml');

echo '<pre>' . json_encode($parser, JSON_PRETTY_PRINT);
