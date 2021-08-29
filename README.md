# PHP Buscar Enderecos

Uma biblioteca para buscar o endereço via cep

## Utilização

Para usar está biblioteca basta seguir os exemplos abaixo:

```Shell
$ composer require sandro/php-search-address
```

```php
<?php

require __DIR__. '/vendor/autoload.php';

use SandroAmancio\Search\Address;

$busca = new Address;

$resultado = $busca->getAddressFromZipCode('01001-000');

print_r($resultado);


```


## Requerimento

- PHP >= 7.0.0 