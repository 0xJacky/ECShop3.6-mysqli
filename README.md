# ECShop3.6 MySQLi CLS
This a MySQLi Common Class Library for ECShop3.x, adds support for PHP mysqli extension, compatibles with PHP 7.x and MySQL5.6+

这是一个 ECShop 3.x 的 MySQLi 公用类库，已支持 PHP MySQLi 拓展，适配 PHP7.x 及 MySQL5.6+

目前已在生产和开发环境下测试兼容 ECShop 3.0/3.6

PS: 为了提升性能，已将原版 MySQL 类库中有判断 PHP / MySQL 版本的相关代码删除

## Usage 用法
1. Please put `cls_mysqli.php` to `includes/ `.
1. 请将 `cls_mysqli.php` 放入到 `includes/` 下。
2. Search and replace `cls_mysql` to `cls_mysqli` in all files.
2. 搜索并替换全局的 `cls_mysql `为 `cls_mysqli`。
