composer install -vvv  
cp .env.example .env  
php artisan key:generate  
php artisan migrate  
php artisan admin:install  
php artisan passport:install  
php artisan storage:link  
