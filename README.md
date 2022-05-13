### PHP coding best practices

Class names should be `StudlyCase`
```php
class Kernel
{

}
```
Class variables name should be `camelCase`
```php
public array $middlewareGroups = [];
```
Method names should be `camelCase`
```php
public function bootstrap(): void
{

}
```
Function and Variable names should be `snake_case`
If we go to PHP core, we will see that all functions is declared with `snake_case`,
and we should follow this convention
```php
str_contains();
preg_match();

$app = app();
```
In one file should be only one `class`
Constant names should be declared in `uppercase` and with `underscore` separator
```php
public const PER_PAGE = 10;

```
`declare(strict_types=1)` is required
On the every PHP file, you should enable strict mode
```php
<?php

declare(strict_types=1);
```
`Static types` should be used whenever possible
```php
public function bootstrap(): void
{
    
}
```

