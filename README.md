# Pint Preset

A default configuration preset for [Pint](https://laravel.com/docs/12.x/pint), the Laravel automatic code formatter.

This preset provides a consistent, opinionated style guide for Laravel and PHP projects.  
It can be easily reused across multiple repositories to ensure uniform formatting rules.

## Installation

Add the preset to your project via Composer:

```
composer require breuermarcel/pint-preset --dev
```

## Usage

In your `pint.json` file, extend this preset:

```
{
    "preset": "breuermarcel/pint-preset"
}
```

Then run Pint as usual:

```
./vendor/bin/pint
```

## License

This project is open-sourced under the [MIT license](LICENSE).
