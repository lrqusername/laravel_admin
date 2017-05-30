### 安装说明
* clone代码到本地, `git clone https://github.com/lrqusername/laravel_admin.git`
* 配置 `.env` 文件，将 `.env.example` 复制一份修改为 `.env` ，并修改数据库连接
* 执行 `php artisan key:generate` 
* 执行 `php artisan migrate` 迁移数据库
* 执行 `php artisan db:seed` 填充数据库
* 本地设置虚拟域名到根目录下的public
* 默认账号：admin 密码：admin
