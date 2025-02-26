youtube link: https://www.youtube.com/watch?v=iVThaG_sAt0&ab_channel=TheCodeholic
repo: https://github.com/thecodeholic/laravel-10-blog

links:
https://laravel.com/
https://filamentphp.com/

create a new project:
`composer create-project laravel/laravel example-app`
`composer global require laravel/installer`
`laravel new example-app`
sudo bash to go root
`curl -s https://laravel.build/example-app | bash`

```
cd example-app
./vendor/bin/sail up
```

`./vendor/bin/sail artisan migrate`

`composer require filament/filament:"^3.2" -W`

`php artisan filament:install --panels`

permission issues when localhost not loading give it this commands in terminal in the root folder on project
`sudo chown www-data:www-data -R ./storage`
`sudo chown www-data:www-data -R ./storage`

9:12
