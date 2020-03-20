# Lumen PHP Framework
https://auth0.com/blog/developing-restful-apis-with-lumen/
- https://packagist.org/packages/laravel/tinker
- https://laracasts.com/discuss/channels/general-discussion/where-is-php-artisan-tinker-in-lumen
- check connect to DB
```bash
$ php artisan tinker
   DB::connection()->getPdo();
$ php artisan migrate
$ php -S localhost:8000 -t public   
```
input json
```json
{
	"name": "ABC",
	"email": "abc@gamil.com",
	"github": "abc1",
	"twitter": "abc2",
	"location": "abc3",
	"latest_article_published": "2017-12-18 21:58:24"
}
```
