![image](https://img.shields.io/badge/version-v1.0-green)
2
​
3
​
4
![image](https://img.shields.io/badge/author-liqiqiorz-yellow)
5
![image](https://img.shields.io/badge/build-passing-brightgreen)
6
​
7


author:liqiqiorz

改自其它项目 整合vue-admin-master项目

gin+vue的前后端分离


# gin-vue
### 注意：本项目没有使用Go Modules，所以请先关闭它或设置成auto，不然会出现一些问题。
运行指令：`go env -w GO111MODULE=off`或者`go env -w GO111MODULE=auto`


该项目是gin+vue的前后端分离项目，使用gorm访问MySQL

使用jwt，对API接口进行权限控制。

jwt已经整合中间件:gin_jwt

直接实例化使用即可

vue-admin-master项目已经全局注册header附带token

所以请求不需要额外加其它乱七八糟的

在token过期后的半个小时内，用户再次操作会自动刷新token

### go后台程序运行方式

1.在MySQL中新建blog数据库，运行文件夹/docs/sql中的mysql.sql脚本

2.在文件夹/conf中修改配置文件api.ini中的数据库连接配置

3.在gin-vue目录下运行`go run main.go`

### vue运行方式请看文件夹/vue-admin中的README.md
