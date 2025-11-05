

## Instruction 
============run those =============
=> npm run dev 
=> php artisan ser

=> migration : php artisan migrate

=> then there have a db seeder for admin user :
run command ::   php artisan db:seed --class=CreateAdminUser

## access of admin is 

email: admin@gmail.com
Pass: 123456

then there have specialy two routes one for event : http://localhost:8000/dummy-posts-store

and then you can show result that's means echo receiving events on route:  http://localhost:8000/posts

that's a so simple project for getting realtime notification while an event happen. 

## Note: 
Have to populate pusher info properly 

BROADCAST_CONNECTION=pusher

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_APP_CLUSTER=
PUSHER_PORT=
PUSHER_SCHEME=

you may get this from https://dashboard.pusher.com/apps/2072665/keys , that's link be accessable after loged in ppusher site. 



## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
