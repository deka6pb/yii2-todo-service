Installation
============

Step 1: Composeer update
------------------------------

```bash
$ php composer update update
```

Step 2: Yii init
------------------------------

```bash
$ php init
```

Step 3: Update database schema
------------------------------

> **NOTE:** Create new database and edit your common/config/main-local.php

> **NOTE:** Make sure that you have properly configured **db** application component.

After you downloaded and configured Yii2-todo-service, the last thing you need to do is updating your database schema by
applying
the migrations:

```bash
$ yii migrate
```
```bash
$ php yii migrate/up --migrationPath=@vendor/deka6pb/yii2-simple-todo/migrations
```