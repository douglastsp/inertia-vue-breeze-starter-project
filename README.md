## Inertia | Vue | Breeze | Tailwind | Starter Project

This is a setup to start projects with Inertia, Vue, Breeze and Tailwind.

### Run to install

```sh
cp .env.example .env
```

```sh
composer install
```
```sh
php artisan key:generate
```
```sh
php artisan storage:link
```
```sh
npm install
```

### If you're using docker you could have some problems with hotreload

```javascript
server: {
        hmr: {
            host: 'yourdomain',
        },
    },
```

And then run npm run dev 

```sh
npm run dev
```