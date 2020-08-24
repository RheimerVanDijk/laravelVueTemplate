Deploy laravel onto vps:
https://devmarketer.io/learn/deploy-laravel-5-app-lemp-stack-ubuntu-nginx/

When updating your application run:

```
php artisan key:generate
php artisan cache:clear
php artisan config:clear
```

setup after clone

1.

```
composer install
```

2.

```
npm install
```

or

```
yarn
```

3.

```
cp .env.example .env
```

4.

jwt setup:
https://jwt-auth.readthedocs.io/en/develop/laravel-installation/

5.

```
php artisan key:generate
php artisan jwt:secret
```
