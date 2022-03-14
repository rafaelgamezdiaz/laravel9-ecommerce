<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>


## Laravel 9 Ecommerce

Laraver 9 + Sail + JetStream + Livewire

Is was implementing with an HTML template


### Steps 
- Install Latavel with Sail (only add mysql, or the desired database)
- Change database credentials following the guide [laravel-notes](https://github.com/rafaelgamezdiaz/laravel-notes/blob/main/chuleta.md)
- Up containers: ./vendor/bin/sail up
- Install livewire: composer require livewire/livewire
- Mount the template, use: sail php artisan make:livewire HomeComponent to create the livewire components
- Configure the routes, and the components
- Install JetStream to implement the authentication: sail composer require laravel/jetstream
- php artisan jetstream:install livewire
- Run migrations

