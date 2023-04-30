### Project install
`
git clone https://github.com/arekadaw/laravel-crud-authentication
`

### Vendor folder and other files
`
composer update
`

Copy **.env.example** file rename to **.env**

### Project key generate
`
php artisan key:generate
`

### Database connection
Create database and create find these fields in the .env file and enter your information

`
DB_DATABASE=laracrudauth
DB_USERNAME=root
DB_PASSWORD=
`

### Cache clear
`
php artisan config:cache
`

### Make migrate
`
php artisan migrate
`

### Make seed
`
php artisan db:seed
`

### Run project
`
php artisan serve
`  
### Login info 
`
email    : areka@areka.com
password : 123456
`
