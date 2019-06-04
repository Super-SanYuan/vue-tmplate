# vue-smart-cloud

Vue项目快速模板

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

```Markdown
│── pubilc
│   │── index.html             // html模板
├── src                        // 源代码
│   ├── api                    // 所有请求
│   ├── assets                 // 主题 字体等静态资源
│   ├── components             // 全局公用组件
│   ├── config                 // 配置相关
│   ├── directive              // 全局指令
│   ├── filtres                // 全局 filter
│   ├── icons                  // 项目所有 svg icons
│   ├── styles                 // 全局样式
│   ├── utils                  // 全局公用方法
│   ├── views                  // view
│   ├── App.vue                // 入口页面
│   ├── main.js                // 入口 加载组件 初始化等
│   ├── router.js              // 路由
│   ├── store.js               // 全局 store管理
├── .browserslistrc            // 浏览器兼容配置
├── .babel.config              // babel-loader 配置
├── .eslintrc.js               // eslint 配置项
├── .gitignore                 // git 忽略项
├── package.json               // package.json
├── package-lock.json          // 依赖版本锁
├── postcss.config             // CSS 处理工具配置
└── README.md                  // 项目说明
```

```Markdown

// eslint需要依赖
"babel-eslint": "^10.0.1",
"eslint": "^4.15.0",
"eslint-config-standard": "^10.2.1",
"eslint-friendly-formatter": "^4.0.0",
"eslint-loader": "^1.7.1",
"eslint-plugin-import": "^2.7.0",
"eslint-plugin-node": "^5.2.0",
"eslint-plugin-promise": "^3.4.0",
"eslint-plugin-standard": "^3.0.1",
"eslint-plugin-vue": "^4.0.0",
"prettier": "^1.16.4",
```
