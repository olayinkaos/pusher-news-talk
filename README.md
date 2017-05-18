# News Talk 🗣
Simple real-time [Laravel](https://laravel.com) application, with desktop notifications powered by [Pusher](https://pusher.com/)
To test this app locally:
1. Clone this repo -- `git clone https://github.com/olayinkaos/pusher-news-talk.git`.
2. Copy `.env.example` to `.env` and configure your local environment variables, *especially the database and pusher settings*.
3. Install all dependencies -- `composer install && npm install`
4. Generate a new application key - `php artisan key:generate`
5. Migrate the database tables -- `php artisan migrate`
6. Edit in your Pusher App Key in `resources/assets/js/bootstrap.js`.
7. Run using your local web server, or PHP's built-in option - `php artisan serve`
