#  webpack

## 一、webpack安装

- 全局安装webpack

  `npm i webpack webpack-cli -g`

- 项目中安装webpack (推荐)

  `npm i webpack webpack-cli -D`

> 1. 初始化项目 `npm init -y`
> 2. 安装webpack `npm i webpack webpack-cli -D`



## 二、webpack使用

### 2.1 webpack-cli

npm 5.2 以上的版本提供了一个`npx`指令 [npx传送门](http://www.ruanyifeng.com/blog/2019/02/npx.html)

npx 想要解决的主要问题，就是可以直接调用项目内部安装的模块(未在全局安装的第三方模块"-g"，如直接使用"-D"安装到项目中的第三方模块)，原理就是在`node_modules`下的`.bin`目录中找到对应的命令执行

使用webpack命令：`npx webpack`

webpack4.0之后可以实现0配置打包构建，0配置的特点就是限制比较多，无法自定义很多配置(如 无法指定入口和输出等)

开发中常用的还是使用webpack配置进行打包构建