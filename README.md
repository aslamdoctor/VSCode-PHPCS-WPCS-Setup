# VSCode + PHPCS + WPCS Setup

This repository is only used for setting up VSCode properly for WordPress projects the uses [Understrap Theme](https://github.com/understrap/understrap). So that the code can follow proper WordPress coding standards.

## Required VSCode Extension

- [PHP Sniffer & Beautifier](https://marketplace.visualstudio.com/items?itemName=ValeryanM.vscode-phpsab)

## Packages Used

- [php-stubs/acf-pro-stubs](https://packagist.org/packages/php-stubs/acf-pro-stubs) -  Advanced Custom Fields PRO stubs for static analysis
- [wp-coding-standards/wpcs](https://packagist.org/packages/wp-coding-standards/wpcs) - PHP_CodeSniffer rules (sniffs) to enforce WordPress coding conventions

## Steps to use

- Clone the repo in your wordpress theme folder
- Run `composer install`
- Done 🎉