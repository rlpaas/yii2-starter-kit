Yii2 Starter Kit

Using Kartik Practical-B project Template, Dektriun Yii User and mdm soft admin (rbac)

After clone

Run composer update

Assign your database on config/db.php

Then run -  php yii migrate/up --migrationPath=@vendor/dektrium/yii2-user/migrations


Then run -  php yii migrate --migrationPath=@yii/rbac/migrations