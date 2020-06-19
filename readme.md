## Laravel 6 Default Authentication System

### 1. Install laravel

	1. composer create-project laravel/laravel==6.0.2 ka-lauth

### 2. Remove 'public' from the end-point / url

	1. create an index.php in root directory
	   > copy server.php and rename it to index.php

	2. create .htaccess file
	   > copy it from root/public dir
	   > paste it in root dir
	   
	3. run the server 

### 3. Create database

	1. Create database
	2. Add database credentials to .env file


### 4. 27. Laravel Default Authentication Login, Register	

	1. Create routing and views for authentication 
		> composer require laravel/ui "^1.0" --dev
		> php artisan ui vue --auth

	2. Add bootrap css and js to
		>  app.blade.php

	3. Create table 
		> php artisan migrate

	4. Register a new user 