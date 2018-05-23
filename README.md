# Slow Query Logger for Laravel

## Quickstart

```
composer require rokde/laravel-slow-query-logger
```

Add to `providers` in `config/app.php`:

```
Rokde\LaravelSlowQueryLogger\LaravelSlowQueryLoggerProvider::class,
```

## Installation

Add to your composer.json following lines

	"require": {
		"rokde/laravel-slow-query-logger": "~0.0"
	}

Add `Rokde\LaravelSlowQueryLogger\LaravelSlowQueryLoggerProvider::class,` to `providers` in `config/app.php`.

Run `php artisan vendor:publish --provider="Rokde\LaravelSlowQueryLogger\LaravelSlowQueryLoggerProvider"`

## Configuration

### `time-to-log`

Only log queries longer than this value in microseconds.

### `environments`

Set the enabled environments to log slow queries.

### `log-level`

Set the log-level for logging the slow queries.

## Usage

Nothing to do after adding to `/config/app.php`. Watch your logs.
