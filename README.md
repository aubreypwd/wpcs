# wpcs

Just a package you can install with either Composer and/or NPM and it will automatically install WordPress Coding Standards for you:

To get both PHP and JavaScript support, follow both of the steps below...

## PHP

### Installation

```bash
composer require aubreypwd/wpcs --dev
sh vendor/aubreypwd/wpcs/phpcs-install.sh
```

- Uses `WordPress-Extra` 
- Minimum PHP Support: 5.6+

## JavaScript

### Installation

```bash
npm install @aubreypwd/wpcs
sh node_modules/@aubreypwd/wpcs/js-install.sh
```

- Uses `@wordpress/eslint-plugin/recommended` and disables any `prettier/prettier` rules.
