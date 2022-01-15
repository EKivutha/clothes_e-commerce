## About
This is a ecommerce project for selling clothing and shoes in kenya  
One can place orders and expect delveries within 24hrs  
It is using a postgresql backend and database,  
with Sail for container management
## Running
run ```docker run --rm \  
    -u "$(id -u):$(id -g)" \
    -v $(pwd):/var/www/html \
    -w /var/www/html \
    laravelsail/php81-composer:latest \
    composer install --ignore-platform-reqs```
run  `php artisan serve`
For tests` sail test` / `sail dusk`
## Sample screens

To be updates  