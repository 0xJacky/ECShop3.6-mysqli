# ECShop3.0_mysqli
This a mysqli driver for ECShop3.0, added support for PHP mysqli extension, compatibled with PHP 7.x and MySQL5.6+

此 mysqli 类库在原 ECShop 3.0 的 mysql 类库上修改而成，已支持 PHP mysqli 拓展，适配 PHP7.x 及 MySQL5.6+

# Usage 用法

1. 请将 cls_mysqli.php 放入到 includes/ 下
2. 搜索并替换全局的 cls_mysql 为 cls_mysqli
3. 进入 data/config.php 中添加
```
$db_adress = "YOUR_DB_ADRESS";
$db_port = "YOUR_DB_PORT";
```
### 配置完成后进入网站，检查兼容性，如有 BUG，请提交 Issues

Author: 0xJacky
