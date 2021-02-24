# PHP - Lumen Framework - RESTfull API
RESTfull API build on :
- PHP Language
- Laravel Base
- Lumen Framework
- MVC Pattern
- Depedencies : Eloquent, Facades.
- MariaDB
## Installation
PHP required v7.3.* or Higher to run
MariaDB required v10.* to run
or with XAMPP [Link](https://www.apachefriends.org/download.html) / Laragon
```sh
- Download or Clone from Github -
cd lumen_restfullapi_basic
cp .env.example .env
```
Edit this line
```sh
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE={yourdatabase}
DB_USERNAME={yaourusername}
DB_PASSWORD={yourpassword}
```
Running Code
```sh
php -S localhost:8000 -t public
```
## API Endpoint
| METHOD | ENDPOINT | Description |
| ------ | ------ | ------ |
| GET | http://{yourhost}:8000/api/authors | GET ALL Authors |
| GET | http://{yourhost}:8000/api/authors/{id} | GET ONE Authors  |
| POST | http://{yourhost}:8000/api/authors | CREATE Authors |
| PUT | http://{yourhost}:8000/api/authors/{id} | UPDATE Authors |
| DELETE | http://{yourhost}:8000/api/authors/{id} | DELETE Authors |

## Postman Collection
File on Directory demo/postman

## License
MIT
