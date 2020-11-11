# Web-BeeFlix

COMP6051 Web Programming<br/>
2020-2021 Odd Semester<br/>
Mid Exam mini project


## Brief

A simple website-based application to show a list of movies based on its genre, then display the details of each movie from database.


## Creative Thinking

  * Separate components (such as header, footer, and movie card) into several blade files.
  * Create an abstract `BaseMovieSeeder` class to support some custom functions.

  
## Deployment

  * Create MySQL database named `beeflix` on `127.0.0.1:3306` with `root` username and no password. You can customize the ip address, port, database username or password based on your own machine setup.
  * Run `composer install` to download all dependencies needed.
  * Run `cp .env.example .env && php artisan key:generate` to prepare all important data.
  * Run `php artisan migrate --seed` to create and fill the database.
  * Run `php artisan serve` and access the webapp on localhost port 8000.


## References

Here is a list of accessed references during the development phase

  * [Laravel Blade Documentation](https://laravel.com/docs/7.x/blade)
  * [Bootstrap Full Documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/)


Here is a list of content (art, description, rating, etc) sources that are crawled from another website

  * [Boku Dake ga 17-sai no Sekai de](https://mydramalist.com/53361-boku-dake-ga-17-sai-no-sekai-de)
  * [Koi wa Tsuzuku yo Doko Made mo](https://mydramalist.com/51965-koi-wa-tsuzuku-yo-doko-made-mo)
  * [Itazura na Kiss: Love in Tokyo](https://mydramalist.com/6535-itazura-na-kiss-love-in-tokyo)
  * [Hospital Playlist](https://mydramalist.com/36269-doctor-playbook)
  * [It's Okay to Not Be Okay](https://mydramalist.com/49865-psycho-but-it-s-okay)
  * [Prison Playbook](https://mydramalist.com/22624-wise-prison-life)
  * [1 Litre no Namida](https://mydramalist.com/2-1-litre-no-namida)
  * [Boku no Ita Jikan](https://mydramalist.com/8507-boku-no-ita-jikan)
  * [Liar Game](https://mydramalist.com/40-liar-game)

  * [Tonari no Totoro](https://myanimelist.net/anime/523/Tonari_no_Totoro)
  * [Stand By Me Doraemon](https://myanimelist.net/anime/21469/Stand_By_Me_Doraemon)
  * [Chocolate Underground](https://myanimelist.net/anime/3962/Chocolate_Underground)
  * [Rilakkuma to Kaoru-san](https://myanimelist.net/anime/35777/Rilakkuma_to_Kaoru-san)
  * [Ojamajo Doremi Sharp Movie](https://myanimelist.net/anime/2947/Ojamajo_Doremi_Sharp_Movie)
  * [Motto! Ojamajo Doremi: Kaeru Ishi no Himitsu](https://myanimelist.net/anime/2948/Motto_Ojamajo_Doremi__Kaeru_Ishi_no_Himitsu)
  * [Doraemon Movie 31: Shin Nobita to Tetsujin Heidan - Habatake Tenshi-tachi](https://myanimelist.net/anime/10534/Doraemon_Movie_31__Shin_Nobita_to_Tetsujin_Heidan_-_Habatake_Tenshi-tachi)
  * [Pokemon Generations](https://myanimelist.net/anime/34514/Pokemon_Generations)
  * [Pokemon (2019)](https://myanimelist.net/anime/40351/Pokemon_2019)

  * [EXO's Showtime](https://mydramalist.com/25743-exo-s-showtime)
  * [Busted](https://mydramalist.com/26034-the-culprit-is-you)
  * [Hyori's Bed And Breakfast](https://mydramalist.com/25626-hyori-s-bed-and-breakfast)
  * [Produce 101: Season 2](https://mydramalist.com/25620-produce-101-season-2)
  * [Hana yori Dango 2 (Returns) Bangai hen: Makinoke Hajimete no Kazoku Ryoko in N.Y.](https://mydramalist.com/2205-hana-yori-dango-special)
  * [Run BTS! Season 1](https://mydramalist.com/25817-run-bts-season-1)
  * [Busted 2](https://mydramalist.com/29228-busted-2)

<hr/>

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
