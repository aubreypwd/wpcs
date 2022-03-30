# wpcs

Just a package you can install with either Composer or NPM and it will automatically install WordPress Coding Standards for:

## PHP

### Installation

```bash
composer require aubreypwd/wpcs --dev
```

### Usage

```bash
ln -sf ./vendor/aubreypwd/wpcs/.phpcs.xml.dist ./.phpcs.xml.dist
ln -sf ./vendor/aubreypwd/wpcs/.editorconfig ./.editorconfig
```

- Uses `WordPress-Extra`

## JavaScript

### Installation

```bash
npm install @aubreypwd/wpcs --save-dev
```

### Usage

```bash
ln -sf ./node_modules/@aubreypwd/wpcs/.eslintrc ./.eslintrc
ln -sf ./vendor/aubreypwd/wpcs/.jshintrc ./.jshintrc
```

- Uses `@wordpress/eslint-plugin/recommended` and disables any `prettier/prettier` rules.

---------

# Symlinks

If you plan on changing any of these configurations, copy instead of symlink and modify instead.
