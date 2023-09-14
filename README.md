# Dikki DotEnv - Just Another DotEnv Component for PHP

This DotEnv component was ripped off from CodeIgniter 4 and created as a standalone component. It is a simple class that
loads a `.env` file in the project root and sets the environment variables from it.

## Usage

```php
$dotenv = new Dikki\DotEnv\DotEnv(__DIR__); // directory where .env is present
$dotenv->load(); // load the vars from .env file

echo $_ENV['DEBUG']; // or getenv('DEBUG')
```