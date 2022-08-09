<p align="center"><a href="https://github.com/msucevan/laravel-swapi-project" target="_blank"><img src="https://getwallpapers.com/wallpaper/full/0/d/0/1513692-star-wars-yoda-wallpaper-3840x2160-full-hd.jpg" width="400"></a></p>

<p align="center">
<img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status">
<a href="https://opensource.org/licenses/MIT" targe="_blank"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Swapi Project

Laravel Swapi Project is an api build to show people and their related planets from <a href="https://swapi.dev/">SWAPI - The Star Wars API</a>


## Installation

Clone the repository in your local enviroment

```https://github.com/msucevan/laravel-swapi-project.git ```

Build the project image

```docker build -t laravel-swapi-project . ```

And/or just run

```docker-compose up -d```




API endpoints

```
http://localhost:8080/planet            // Get the list of all planets
http://localhost:8080/people            // Get the list of all people
http://localhost:8080/planet/{id}       // Get the details about the planet
http://localhost:8080/people/{id}       // Get the details about the planet
```

## Laravel Sponsors

