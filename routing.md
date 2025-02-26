# Routing
Routing di Gampil cukup mudah karena memakai array associative yang bisa dibilang "konstan" sehingga performanya tidak terlalu berat.

## Format

```php
<?php
// 'route' => ['controller:method', 'request_method'] (default `request_method` = 'GET')
return [
  '/' => ['dummy:home'],#nama controller harus sama dengan file controller
  '/about' => ['basic:about'],
  '/register' => ['auth:register_view'],
  '/register' => ['auth:register', 'POST']
];
```