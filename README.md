# Blade Shortcuts

[![Latest Version on Packagist](https://img.shields.io/packagist/v/djl997/blade-shortcuts.svg?style=flat-square)](https://packagist.org/packages/djl997/blade-shortcuts)
[![Total Downloads](https://img.shields.io/packagist/dt/djl997/blade-shortcuts.svg?style=flat-square)](https://packagist.org/packages/djl997/blade-shortcuts)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

Blade Shortcuts is a library of handy Blade Directives as listed below.

## Requirements
Blade Shortcuts requires PHP 8+ and Laravel 6+.

## Installation
You can install the package via composer:
```bash
composer require djl997/blade-shortcuts
```

## Usage
After installation all blade directives should be usable. Try running `php artisan view:clear` if the directives are not working properly or if they are not updating. 

### Boolean
```blade
@boolean(true) <!-- true -->
@boolean(false) <!-- false -->
```

### Filesize
```blade
@filesize(2145) <!-- 2 kB -->
@filesizemb(124588) <!-- <1 MB -->
@filesizegb(1198466000) <!-- 1,1 GB -->
```
## Contributing

Contributions are welcome.

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.