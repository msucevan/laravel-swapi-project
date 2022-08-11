<p align="center"><a href="https://github.com/msucevan/laravel-swapi-project" target="_blank"><img src="https://getwallpapers.com/wallpaper/full/0/d/0/1513692-star-wars-yoda-wallpaper-3840x2160-full-hd.jpg" width="400"></a></p>

<p align="center">
<img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status">
<a href="https://opensource.org/licenses/MIT" targe="_blank"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Swapi Project

Laravel Swapi Project is an api build to show people and their related planets from <a href="https://swapi.dev/">SWAPI - The Star Wars API</a>


## Installation

Clone the repository in your local enviroment

```git clone https://github.com/msucevan/laravel-swapi-project.git ```

Build the project image

```docker build -t laravel-swapi-project . ```
OR
```docker-compose build```

And/or just run

```docker-compose up -d```

Request the bash console to the application container with the alias name: php

```docker exec -it php bash```

```composer require msucevan\swapi```

```composer install```

Then, run laravel artisan migrations

```php artisan migrate```


Then, run laravel artisan command to create a new universe

```php artisan create-universe```


Now this API endpoints are available

```
http://localhost:8080/people            // Get the list of all people
http://localhost:8080/people/{id}       // Get the details about the person and the details about the related planet
```

