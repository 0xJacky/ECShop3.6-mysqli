# ECShop3.0_mysqli
This a database driver for ECShop3.0, in order to support PHP7.x
此 mysqli 类库在原 ECShop 3.0 的 mysql 类库上修改而成，目的在于适配 PHP7.x

#Usage 用法

1. 请将 cls_mysqli.php 放入到 includes/ 下
2. 替换全局的 cls_mysql 为 cls_mysqli
3. 进入 data/config.php 中添加
```
$db_adress = "YOUR_DB_ADRESS";
$db_port = "YOUR_DB_PORT";
```
4. 进入网页，检查兼容性
5. 如有 BUG，请提交 Issues

Author: 0xJacky
