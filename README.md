
## Installation & Running

To install Laravel with Vuetify frontend built on top of InertiaJs you need to use commands:

```bash
    composer install
    yarn / npm install
```

Then you will need to use migrations
```
php artisan migrate
```


Then to start your servers:

```
php artisan serve
php artisan inertia:start ssr
yarn dev / npm run dev
```



## Environment Variables

To run this project, you will need to add the environment variables to your .env file (Copy .env.example)