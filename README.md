# Laravel set up 

* Downloaded the composer using brew,
	i.e. brew install composer

* Downloaded laravel installer using the composer,
	i.e. composer global require "laravel/  			 installer=~1.1"

* Installed laravel via homebrew,
	i.e. brew install laravel

* Added a path to laravel as:
	export PATH=$PATH:~/.composer/vendor/bin

* Created a new laravel directory as:
	laravel new [name] 

	e.g.
		laravel new mouse

* Created a new application key as:
	php artisan key:generate

* Changed directory to the one with the app folder, then renamed the app folder.
E.g.
	php artisan app:name tripped

		tripped is the name of the application

* Accessed the Homestead.yaml and host files and modified them to add the tripped application.

## CircleCI
* Signed in via github
* Added the repo to be tested
* Updated the PHP version of CircleCI
* Added the environment variable (generated using php artisan key:generate) to the CircleCI project folder
