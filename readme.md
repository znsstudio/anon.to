# anon.to
[anon.to](https://anon.to) is an anonymous url redirector and url shortener build using [laravel](https://laravel.com/)

### Requirement
- [**PHP**](https://php.net) 5.5.9+ or [HHVM](http://hhvm.com) 3.3+
- PHP Extensions: openssl, mcrypt and mbstring
- Database server [MySQL](https://www.mysql.com) or [**MariaDB**](https://mariadb.org)
- [Redis](http://redis.io) Server
- [Composer](https://getcomposer.org).
- [NodeJs](https://nodejs.org/) with npm

### Installation
* clone the repository `git clone https://github.com/bhutanio/anon.to.git anon.to`
* create a database
* Create configuration env file `.env` refer to `.env.example`
* install `composer install --no-dev`
* setup database tables `php artisan migrate`

### License
The anon.to is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)