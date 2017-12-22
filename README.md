# thai-CRM

run this step:
1. git clone https://github.com/thai-laravel/thai-CRM.git
2. cd thai-CRM/
3. php artisan cache:clear
4. composer install
5. mkdir storage
6. mkdir storage/framework
7. mkdir storage/framework/sessions
8. mkdir storage/framework/views

9. create file ".env" and pass this value:
```
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_LOG_LEVEL=debug
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

BROADCAST_DRIVER=log
CACHE_DRIVER=file
SESSION_DRIVER=file
SESSION_LIFETIME=120
QUEUE_DRIVER=sync

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_DRIVER=smtp
MAIL_HOST=smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
```

10. run this command "php artisan key:generate"

11. and run "php artisan serve"

enjoy!!.
