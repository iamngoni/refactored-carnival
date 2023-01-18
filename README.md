## Knowledge Test

### Migrating tables
```shell
$ php artisan migrate
```

- if facing any issues then you may migrate roles table first alone
```shell
php artisan migrate --path=/database/migrations/2023_01_18_055435_create_roles_table.php
```

### Running
```shell
$ php artisan serve
```
