# Dikki DotEnv - Just Another DotEnv Component for PHP

A simple dotenv component for PHP.

## Usage

```php
$dotenv = new Dikki\DotEnv\DotEnv(__DIR__, '.env'); // directory where .env is present; second argument is optional
$dotenv->load(); // load the vars from .env file

echo $_ENV['DEBUG']; // or getenv('DEBUG')
```
