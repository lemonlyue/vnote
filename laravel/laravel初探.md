# 毕业设计
## 一、安装laravel
1. composer install 进行安装
`composer install`
2. 生成.env文件
`cp env-example .env`
3. 设置应用程序加密密钥
提示：
`No application encryption key has been specified`
使用命令：`php artisan key:generate`生成