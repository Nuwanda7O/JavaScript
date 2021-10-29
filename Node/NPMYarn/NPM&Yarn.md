### 认识什么是NPM？

全称Node Package Manager

### 安装

安装完毕node后默认安装好npm

npm也是基于node开发的软件

> 。。。我这个mac好像系统自带了 不需要再到官网下载了

`node -v` 查询版本

`npm -v` 查询版本

`npm install npm -g` 用npm全局安装了所有版本的npm

如果想安装到某个项目中 命令行进入项目再安装 不要使用 -g 如下：

<img src="/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午1.34.11.png" alt="截屏2021-10-29 下午1.34.11" style="zoom:50%;" />

`npm config get registry` 查看当前镜像配置

`npm config set registry https://registry.npm.taobao.org` 淘宝镜像

`npx nrm use taobao` 使用nrm工具切换到淘宝源

`npx nrm use npm` 	切换回官方源

### 基本使用

- npm list -g 查看全局安装的模块
- npm list vue 查看某个模块的版本 比如vue
- npm i jquery@版本号 指定版本安装
- npm update jquery 更新至最新版本
- npm uninstall jquery 删除

![截屏2021-10-29 下午2.11.15](/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午2.11.15.png)

现在没有配置项区别 但有属性dev:"true" 

### package.json文件属性

![截屏2021-10-29 下午1.56.21](/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午1.56.21.png)

`nom init --yes` 自动生成配置文件 不加yes的话就手动输入信息

- name 包名
- npm run test 执行test中写的命令

拿到别人的程序 先npm install一下下载好配置文件

### 包的使用

![截屏2021-10-29 下午2.21.15](/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午2.21.15.png)

## Yarn

### 使用原因？

- npm 安装下载慢
- 多人开发时 由于安装本不一致出现bug

### 安装使用

- npm install yarn -g 使用npm全局安装
- yarn -v查看版本
- 设置淘宝镜像方法同npm
- init 初始化同npm
- 其他很多操作。。。。用到再学吧 比较简单 只是包管理工具而已![截屏2021-10-29 下午5.03.03](/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午5.03.03.png)

### 优点

![截屏2021-10-29 下午5.04.41](/Users/douqiyuan/Library/Application Support/typora-user-images/截屏2021-10-29 下午5.04.41.png)