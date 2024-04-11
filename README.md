# Задание 3. Установка Laravel

## Ответы на вопросы

1. Перечислите список composer-пакетов, которые использует фреймворк Laravel после установки.

```
 "require": {
        "php": "^8.2",
        "laravel/framework": "^11.0",
        "laravel/tinker": "^2.9"
    },
    "require-dev": {
        "fakerphp/faker": "^1.23",
        "laravel/pint": "^1.13",
        "laravel/sail": "^1.26",
        "mockery/mockery": "^1.6",
        "nunomaduro/collision": "^8.0",
        "phpunit/phpunit": "^11.0.1",
        "spatie/laravel-ignition": "^2.4"
    },
```

2. Изучите директорию `config` и опишите какие файлы хранятся в этой директории.

В директории `config` хранятся более подробные настройки, использующие параметры из файла .env 

Содержит следуюшие файлы:
- `app.php`: 
- `auth.php`: 
- `cache.php`: 
- `database.php`: 
- `filesystems.php`: 
- `logging.php`: 
- `mail.php`: 
- `queue.php`: 
- `services.php`: 
- `session.php`: 


3. В какой директории хранятся основные файлы (классы) с бизнес-логикой приложения?

В директории `App` 