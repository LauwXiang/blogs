# tanwanApp前端项目总结

---------------
## 目录
>* [1.项目脚手架](#项目脚手架)
>* [2.webpack配置分析](#webpack配置分析)
>* [3.vue踩过的那些坑](#vue踩过的那些坑)

-----------------

## 1.项目目录结构及脚手架 
<a name="项目脚手架">

### 目录结构
```shell

├── dist                       // 打包文件
├── src                        // 源代码
│   ├── assets                 // 图片文件
|   |── common	               // 公共资源文件，如base.css等
│   ├── components             // 组件
│   ├── router                 // 路由
│   └── utils                  // 全局公用方法  
│   ├── App.vue                // 入口主组件
|   ├── Global.vue             // 全局参数
│   └── main.js                // 入口 加载组件 初始化等
├── .babelrc                   // babel-loader 配置
├── eslintrc.js                // eslint 配置项
├── .gitignore                 // git 忽略项
├── index.html                 // 主页面
|── package.json               // package.json
└── webpack.config.js.json     // webpack配置文件
```
###简述



<!-- ## 2.webpack配置分析
<a name="webpack配置分析">

## 3.vue中的那些坑 
<a name="vue踩过的那些坑"> -->