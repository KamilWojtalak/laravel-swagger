```
composer require "darkaonline/l5-swagger"
```

You can access your documentation at /api/documentation endpoint.  

Alternatively, you can set L5_SWAGGER_GENERATE_ALWAYS to true in your .env file so that your documentation will automatically be generated.  

```
php artisan vendor:publish --provider "L5Swagger\L5SwaggerServiceProvider"
```

```
php artisan l5-swagger:generate
```
