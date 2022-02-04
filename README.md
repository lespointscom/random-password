# random-password
random-password

## Installation
This project uses composer. Copy of mazraara/random-password:  https://github.com/mazraara/random-password

```
$ composer require lespointscom/random-password
```

## Usage
Genrate random password.
```php
<?php

use RandomPassword\Password;

$password = new Password(10);
echo $password->generate();
```
