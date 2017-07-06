yii-app-bootstrap-4
===========
yii-app-bootstrap-4 is a mixture of the Yii 2 Basic and Advanced templates with no backend / frontend separation, but with the database-based user functionality from the advanced template. The other important note is that it is using Bootsrap 4 instead of Boostrap 3. Some additional folders ('components', 'messages') have also been added.

INSTALLATION
------------
Project can be installed and initialized similarly to the [Yii Advanced Template](https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/start-installation.md).

Installing using Composer
~~~
composer create-project -s dev dan-szabo/yii-app-bootstrap-4 folder_name
~~~

For preparing the application, [please follow this guide](https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/start-installation.md#preparing-application). **You only need step 2. and 3.** (In step 2. update
`config/db.php` instead of `common/config/main-local.php`.)
