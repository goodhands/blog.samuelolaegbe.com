## Create a fully functional blog with comments and authentication using Laravel 6: A step by step guide

Have you ever wondered what it would feel like to create a full CRUD application with the new Laravel 6? Whether this is your first time with laravel or you're still in the learning process, this article will guide you on how to create a fully functional blog in no time.

Remember the first step in learning something new is to underestimate its complexity. I have tried to make this post as simple as possible, however you are going to come across some new terms and concepts. Fret not! For I will explain them in clear details.

## Table of contents
+ Prerequisites 
+ The Laravel Pitch
+ Setting up a Laravel 6 project
+ Project Structure
+ Designing the database
+ The Blog Template
+ Controllers 😉
+ Routes
+ Authentication
+ A user can comment
+ Conclusion

## Prerequisites
To be able to follow through with this article you need the following:
* PHP 7.2x
* Composer
* 

## The Laravel Pitch
So you've always heard about Laravel and how it's one of the best modern frameworks out there for web developers and wondered what it really is?
Here is the short version: Laravel will help you save a bunch of time by abstracting the boring and repetitive tasks in web development like database design, data modelling, caching, user sessions, authentication and the likes. Visit the [Laravel docs](https://laravel.com/docs) to learn more.

The Laravel framework is the superpower of the modern day fullstack developer, allowing you to chunk out websites at a speed you could only imagine. We will see an example of that in this article where we will create a full blog with comments in less than a day. The awesomeness of Laravel also includes it's large and progressive community of other [software packages](https://laravel.com/docs/6.x/packages), so if you needed a functionality that Laravel didn't provide out-of-the box you could import a package from the community using [Composer](https://getcomposer.org/). 

Lumen, a lightweight version of Laravel optimized for API development allows you to create REST APIs which you can connect with any frontend technology of your choice.

## Setting up a Laravel 6 project

#### Installing Laravel
Laravel can be installed in two ways:
+ Globally, so you can run `laravel` in your command line.
+ Locally, this is useful when you only want to create a new Laravel project in your current directory.

For this article we will be installing Laravel globally so we can simply run `larvel new blog`  next time we need a Laravel project:

1. Download and install [composer](https://getcomposer.org)
2. Run the following command in the command line:
````
composer global require laravel/installer
````
3. Add Composer's bin directory to your system `$PATH`, this helps to make the `laravel` command executable system wide.

### Adding Composer to `$PATH`
If you are on a **Windows** machine, open you terminal and enter the following command:

````
set PATH=%USERPROFILE%\AppData\Roaming\Composer\vendor\bin
````
**Linux/Mac** users can do the same by running the following command in the terminal:
````
export PATH=∼/.composer/vendor/bin:$PATH
````
### Laravel New

Once we have finished setting up `composer`, we can begin creating our Laravel app. Type the following in your terminal to download the latest version of Laravel which is 7.x at the time of writing this article:
```
 laravel new blog
```




Laravel can be installed through the command line using composer. Open your favourite terminal and `cd` into your preferred project directory and run this command:
````

````

