# 指南

## 介绍

yd-Admin 是一个基于 Vue2.0、vue-cli3.x、 Element-ui 的后台解决方案，目标是为开发中大型项目提供开箱即用的解决方案。包括二次封装组件、utils、hooks、动态菜单、权限校验、按钮级别权限控制等功能。该项目会持续跟进最新技术，并将其应用在项目中。

## 为什么建这个模板站？

有部分刚接触 VuePress 的同学，按照官方教程操作下来会遇到大大小小的问题，特别是文件目录、打包、插件安装这几块内容。如果直接复制官方的仓库又会比较大，所以如果有一个这样的简洁的初始模板，直接启动使用就很方便了。

而且对应的插件能直接看到效果，使用起来更能得心应手。

## 用法

### 第一步

下载 Vuepress Template 的仓库代码

```sh
git clone https://github.com/openHacking/vuepress-template.git
```

### 第二步

安装依赖

```sh
cd vuepress-template
yarn # 或者npm i
```

### 第三步

启动项目，随后即可根据自己的需求修改配置、编写文档内容

```sh
npm run docs:dev
```

### 第四步

打包项目

```sh
npm run docs:build
```

结果会在`docs/.vuepress/`目录下生成一个`dist`文件夹，里面就是打包后的代码
