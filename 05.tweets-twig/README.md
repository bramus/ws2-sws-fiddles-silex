# WS2-SWS-FIDDLES-SILEX - 05 - Tweets + Twig

Introduces the built-in [TwigServiceProvider](http://silex.sensiolabs.org/doc/providers/twig.html), allowing one to use [Twig](http://twig.sensiolabs.org/) within a Silex app.

## Requirements

- [Composer](http://getcomposer.org/)
- PHP 5.4

## Installation

- Get the source and install the dependencies

		$ git clone https://github.com/bramus/ws2-sws-fiddles-silex.git
		$ cd ws2-sws-fiddles-silex/05.tweets-twig
		$ composer install

## Running the project

### Using PHP 5.4

- Open a shell, navigate to the project root and run `php -S localhost:8080 -t public_html public_html/index.php` to start a PHP web server
- Open `http://localhost:8080/` in your browser

### Using your favorite webserver

- Create a virtualhost pointing to the `public_html` folder
- Make sure you've enabled rewriting
	- See [http://silex.sensiolabs.org/doc/web_servers.html](http://silex.sensiolabs.org/doc/web_servers.html) for more info
	- A `.htaccess` for use with Apache is already included