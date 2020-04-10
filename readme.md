![Demo Video](https://media.giphy.com/media/1eAv85RJxLsaIWNgHd/giphy.gif)

# Task

This is the code test sent to applicants for back-end developer roles. Using PHP (preferably OOP and an MVC structure), MySQL and HTML, create a simple application that will allow the user to display a list of events from a database table with three columns - id, event title and event date. Also enable the user to add, edit and delete events. The code will be judged on structure, readability and security. Using Jquery calendar [http://fullcalendar.io/](http://fullcalendar.io/) (or something similar) display these events in a calendar underneath the list of events created above.


# How To Start

- Clone the project.
- Open project folder with terminal.
- Edit .env file with your credentials.
- Run **"sh run.sh"** command or start manually. (it's a shell script for everything)
- Go to localhost:8000 with your browser.

**Base requirements**
- PHP 7+
- MySQL
- NPM / Yarn
- Composer


**Start manually**
composer install;
npm install;
php artisan migrate;
php artisan db:seed;
vendor/bin/phpunit --debug;
npm run production;
php artisan serve;

**Just run server**
> php artisan serve
