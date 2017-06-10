Libsystem
===
使用Express+Mysql搭建的图书馆流通管理系统
---

### 技术栈
* Express-Node.js Web 应用程序框架
* Mysql-最受欢迎的开源数据库
* Handlebars-高效率的语义化模板
* Bootstrap-简洁、直观、强悍的前端开发框架

### 下载
1. 直接下载压缩包文件，然后解压到本地（推荐）.

2. 如果你安装了`git`，也可以使用`git clone`命令下载到本地.
 ```
 git clone https://github.com/lxz612/libsystem.git
 ```

### 运行前准备
  如果你没有安装`Mysql`，我推荐用`wamp`或`xampp`集成开发环境来安装`Mysql`，这样会省去很多不必要的步骤。<br />
  安装好了`Mysql`后，需要按照项目中的“数据库说明”文件先建立数据表，然后在config.js配置好数据库。<br />
  注意：因为我用到了数据库事务处理，所以Mysql的内核引擎务必设置为支持事务的innoDB.

### 运行

1. 通过npm安装本地服务第三方依赖模块(需要已安装Node.js)
 ```
 npm install
 ```

2. 启动Mysql服务

3. 启动node（http://localhost:3000）
 ```
 npm start
 ```
 
### License
  MIT

###从github上拖的代码，修改之后上传
