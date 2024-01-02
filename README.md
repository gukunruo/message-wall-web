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

```
├── mock/                # mock模拟数据
├── node_modules/        # 项目依赖的 node 模块
├── public/              # 公共资源目录
│   ├── favicon.ico      # 网页图标
│   └── index.html       # html模板（单页面应用）
├── src/                 # 源代码目录
│   ├── api/             # 接口
│   ├── assets/          # 静态资源目录，如图片、字体等
│   ├── components/      # 公共组件
│   ├── router/          # 路由目录
│   ├── store/           # Vuex状态管理目录
│   ├── styles/          # 公共样式目录
│   ├── utils/           # 实用工具函数目录
│   ├── views/           # 视图层组件
│   ├── App.vue          # Vue 根组件，也是整个应用的入口
│   └── main.js          # Vue 实例化入口文件，也是整个应用的入口
├── static/              # 静态资源目录 不会被打包
├── .gitignore           # Git管理忽略文件
├── babel.config.js      # Babel 配置文件
├── jsconfig.json        # js 配置文件
├── package.json         # 项目配置文件
├── pnpm-lock.yaml       # 包版本锁文件
├── README.md            # 项目说明文件
└── vue.config.js        # vue-cli配置文件
```