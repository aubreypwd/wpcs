# aubreypwd/wpcs

Just a package I use with either Composer and/or NPM and it will automatically install WordPress Coding Standards for you for PHP and basic JavaScript.

### Installation

See `example-configs` for configurations you can place in your project's root and customize
to your liking. All of these you can simply symlink if you want to use them as-is, e.g.

```bash
ln -sf vendor/aubreypwd/wpcs/example-configs/phpcs/phpcs.xml.dist ./
```

### Distrobution

Just some notes for me on how I distribute this.

- I use `npm version` to bump the version and let it write the `git` tag for me
- For packagist you need to update the package when you push tags up manually
- For npm you have to use `npm publish`