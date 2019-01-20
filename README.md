# mj-house-shop-web
博客管理系统

## 使用

```
    $ git clone http://192.168.0.49/FrontEnd/mj-pay.git
    $ git checkout -b dev origin/dev          切换到开发分支
    $ cd shop-wa                              进入项目文件夹
    $ npm i || cnpm i                         安装插件
    $ npm run dev                             查看开发列表
    $ open http://localhost:8080              浏览器查看效果

    $ npm run build:test                      打包，测试环境 打包完成后,将dist内文件上传/覆盖到测试环境下即可
    $ npm run build:prod                      打包，生产环境
```

## 说明

### 规范(基本要求)：
* 文件夹:
* 文件夹命名 assets, css, fonts, img, js, sass, less, components,  模块文件夹/模块文件命名驼峰
* 缩进:
* 2个缩进(格式化代码工具)
* vue:
* 页面style加scoped属性
* js:
* 尽量使用ES6语法(比如：let map 箭头函数 ...)，判断使用 === 或 !==,方法/变量驼峰命名,避免回调地狱,自定义方法需写注释
* 样式:
* 支持css,sass,less,小写样式名称 - _ 连接符
* html:
* 遵循W3C规范创建(wap端注意头部添加ios手机兼容代码,ios端输入框以及事件不兼容处理)

随机图片
https://picsum.photos/1080/720/?random
