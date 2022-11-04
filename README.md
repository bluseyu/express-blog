# MyBlog

#### 介绍
根据《[VUE3入门级全栈项目实战-博客开发教程(完结)](https://www.bilibili.com/video/BV1t3411F7VH?p=1&vd_source=0ac42703f8a41caff2a16f3c58a71c14)》视频教程 ，按照葫芦画瓢敲的代码，并参考开源代码，完成了这个练手项目。



#### 软件架构
一个Express博客应用，开发环境Node.js，使用 Express框架（版本4.18.1） + sqlite3数据库 +  Vue3前端框架构建的Blog。


#### 项目运行

在安装node.js 后，进行以下操作

1. 进行server 文件夹，进入 cmd 命令行，安装依赖

``` bash
npm install
```
安装结束后，运行以下命令启动后端：
``` bash
node app.js
```
默认后端端口8080

2. 进行client 文件夹，进入 cmd 命令行，安装依赖

``` bash
npm install
```
安装结束后，运行以下命令启动前端：
``` bash
npm run dev
```

3. 在浏览器中输入 `127.0.0.1:5173`，即可浏览博客内容


#### 项目依赖

- 后端依赖：

``` json
{
  "dependencies": {
    "express": "^4.18.1",
    "multer": "^1.4.5-lts.1",
    "sqlite3": "^5.0.11",
    "uuid": "^8.3.2"
  }
}
```

- 前端依赖：

``` json
{
  "dependencies": {
    "@wangeditor/editor-for-vue": "^5.1.12",
    "axios": "^0.27.2",
    "pinia": "^2.0.21",
    "sass": "^1.54.6",
    "vue": "^3.2.37",
    "vue-router": "^4.1.5"
  },
  "devDependencies": {
    "@vitejs/plugin-vue": "^3.0.3",
    "naive-ui": "^2.33.1",
    "node-sass": "^6.0.1",
    "sass-loader": "^10.2.0",
    "vfonts": "^0.0.3",
    "vite": "^3.0.7"
  }
}
```