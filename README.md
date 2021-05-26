# Lemons

Lemons 是一个轻量级的 PHP 框架

## 如何使用

1. 安装

   ```shell
   composer require shinevv/lemons master
   ```

2. 新建index.php文件

   ```php
   require 'vendor/autoload.php';

   use Lemon\Route;

   Route::get('/', function($request, $response){
     return $response->write('Hello lemon');
   });

   Route::run();
   ```

3. 执行内置服务器

   ```shell
   php -S localhost:4000
   ```

4. 访问 localhost:4000
