# web

## Project setup
```
pnpm install
```

### Compiles and hot-reloads for development
```
pnpm run serve
```

### Compiles and minifies for production
```
pnpm run build
```

### Lints and fixes files
```
pnpm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 目录结构
* ├── mock/                &emsp;# mock模拟数据
* ├── node_modules/        &emsp;# 项目依赖的 node 模块
* ├── public/              &emsp;# 公共资源目录
* │   ├── favicon.ico      &emsp;# 网页图标
* │   └── index.html       &emsp;# html模板（单页面应用）
* ├── src/                 &emsp;# 源代码目录
* │   ├── api/             &emsp;# 接口
* │   ├── assets/          &emsp;# 静态资源目录，如图片、字体等
* │   ├── components/      &emsp;# 公共组件
* │   ├── router/          &emsp;# 路由目录
* │   ├── store/           &emsp;# Vuex状态管理目录
* │   ├── styles/          &emsp;# 公共样式目录
* │   ├── utils/           &emsp;# 实用工具函数目录
* │   ├── views/           &emsp;# 视图层组件
* │   ├── App.vue          &emsp;# Vue 根组件，也是整个应用的入口
* │   └── main.js          &emsp;# Vue 实例化入口文件，也是整个应用的入口
* ├── static/              &emsp;# 静态资源目录 不会被打包
* ├── .gitignore           &emsp;# Git管理忽略文件
* ├── babel.config.js      &emsp;# Babel 配置文件
* ├── jsconfig.json        &emsp;# js 配置文件
* ├── package.json         &emsp;# 项目配置文件
* ├── pnpm-lock.yaml       &emsp;# 包版本锁文件
* ├── README.md            &emsp;# 项目说明文件
* └── vue.config.js        &emsp;# vue-cli配置文件
