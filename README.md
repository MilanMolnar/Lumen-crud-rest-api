![PHP Composer](https://github.com/MilanMolnar/Lumen-crud-rest-api/workflows/PHP%20Composer/badge.svg)

# Lumen Simple CRUD REST API
This API is just for practice

  - Full database capabilities
  - Database migrations
  - Create, Read, Read all, Update, Delete funcionalities

# Installation!

> Clone the repository and follow the steps.

Set up your .env file to your desired database!
```sh
cd master
composer install
php artisan migrate
```

# Tech

Used technologies for this project:

* [Laravel/Lumen] - The stunningly fast micro-framework by Laravel.
* [PHP] - for the best web apps!
* [PHP Storm] - Awesome php text editor by jetbrains.
* [MySQL] - Oracles awesome database.
* [Postman] - Back-end developers favorite Front-end :mailbox_with_mail: . 
* [Github] - duh.

# Usage
```sh
php -S localhost:8000 -t public
```

### - Routes and capabilities

| Routes | funtionality |
| ------ | ------ |
| api/authors | [GET] showAllAuthors |
| api/authors/{author_id} | [GET] showOneAuthor |
| api/authors | [POST] createOneAuthor |
| api/authors/{author_id} | [PUT] updateAuthor |
| api/authors/{author_id} | [DELETE] deleteAuthor|



License
----
Free to use, free to modify, free to share.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [MySQL]: <https://www.mysql.com/>
   [Github]: <https://github.com/>
   [Bootstrap]: <https://getbootstrap.com/>
   [jQuery]: <http://jquery.com>
   [Laravel]: <https://laravel.com/>
   [Php]: <https://www.php.net/>
   [PHP storm]: <https://www.jetbrains.com/phpstorm/>
   [Laravel/lumen]: <https://lumen.laravel.com/>
   [Postman]: <https://www.postman.com/>
