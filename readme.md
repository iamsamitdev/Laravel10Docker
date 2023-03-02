## Intall Vendor
docker-compose exec app composer install

## Generate APP_KEY
docker-compose exec app php artisan key:generate

## Clear config env
docker-compose exec app php artisan config:clear