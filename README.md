# Pint Preset for Laravel Projects

A reusable, opinionated formatting preset for [Laravel Pint](https://laravel.com/docs/12.x/pint), Laravel’s official PHP code style fixer.

This package provides a consistent style guide for Laravel and PHP projects, enabling uniform code standards across multiple repositories.

## Features

- Consistent and opinionated code style
- Easy integration into any Laravel or PHP project
- Centralized maintenance of formatting rules
- Suitable for teams and individual developers

## Installation

Install the package via Composer:

```bash
composer require m-breuer/pint-preset --dev
```

## Usage

Configure Pint to use this preset by extending it in your `pint.json`:

```json
{
  "preset": "m-breuer/pint-preset"
}
```

Then run Pint:

```bash
./vendor/bin/pint
```

## Requirements

- PHP 8.1 or higher
- Laravel Pint 1.10 or higher

## License

This package is open-sourced software licensed under the [MIT license](LICENSE).
