# Lumen Route List Display

## Installation

1. Run
    ```
    composer require jslmariano/lumen-routes-list
    ```

2. Add service provider into **/bootstrap/app.php** file.
    ```php
    $app->register(Jslmariano\LumenRoutesList\RoutesCommandServiceProvider::class);
    ```
3. Run ```composer dump-autoload```

## Commands

```
php artisan route:list
```
