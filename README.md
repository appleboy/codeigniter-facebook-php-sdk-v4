# codeigniter-facebook-php-sdk-v4

Intergrate [facebook php sdk v4][1] with [CodeIgniter][2] Framewrok.

## Installation

Using [composer][3] to install Facebook SDK

```
$ composer install
```

Update your Facebook App id and secret on `config/facebook.php`

```php
<?php if ( ! defined('BASEPATH')) exit('No direct script access allowed');

$config['facebook_app_id'] = 'xxxxxxxxxxxxxxxxxxx';
$config['facebook_api_secret'] = 'xxxxxxxxxxxxxxxxxxx';
```

Open your browser and connect `http://localhost/index.php/login/facebook`

[1]: https://github.com/facebook/facebook-php-sdk-v4
[2]: http://ellislab.com/codeigniter
[3]: https://getcomposer.org/
