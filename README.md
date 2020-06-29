![image](https://img.shields.io/badge/version-v1.0-green)
​
​
![image](https://img.shields.io/badge/author-liqiqiorz-yellow)
![image](https://img.shields.io/badge/build-passing-brightgreen)
​

ForeWord:这两天比较闲散,暂时把Aplmu-frontend基本上是最后一个页面交给了学长开发,所以自己的时间突然多了起来.

然而多的时间并没有拿来学习,而是补完了那个高一起就很火的re0

接触re0也是在高一,但是当时486长成这个样子后宫还贼TM漂亮我是真的忍不了,看了两集,遂弃番.

正如上文所说,这两天比较闲散,所以补了这部当年B霸番(其实也是在bilibili的banner看到了要出第二季的消息)

众所周知,死宅的老婆是三月一换的,但是我觉得自己可能是三星期一换,于是我自己断言是已经超越了死宅的存在.

6月初我曾在两天二刷了巨人三季共59集,毕竟最后一次看巨人已经是高考结束后那几个夜晚.

我曾在大约二十天前坚定的相信着:我老婆是三笠 阿克曼

接着聊聊re0

这部番有着浓厚的轻小说风格


12年曾经被我一度看作神作的sword art online


不得不说 re0和SAO真的非常相近(毕竟都是异世界嘛)


如果我高一看的话可能被当成神作吧 蕾姆对486 正好对应Nacl对桐姥爷

然而回归现实 这样的老婆只是可遇不可求的

现在在我看来 蕾姆对486看似坚定信任的情感就像谏山对亚妮的人物描写一样

亚妮 为了一个无法回去的故乡见到父亲---比起继父之前对她的种种行为 感觉这个理由 是败笔:太牵强了

这也丝毫不影响亚妮是我曾经的老婆.

故乡三人组我最喜欢莱纳

也是补完马来篇的后话了

扯远了 又一次...

叙事能力也不行,,,可见我真的很FW 唉

collude:re0只能算佳作


续接:三笠是我老婆

这一点从第一次2014年接触巨人就不会改变!!



可是 现在看起来 这就是个天大的玩笑

你好 蕾姆酱!

![image](https://edu-1014.oss-cn-beijing.aliyuncs.com/TIM%E5%9B%BE%E7%89%8720200629225320.jpg)

她的笑容,就由我来守护!




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
