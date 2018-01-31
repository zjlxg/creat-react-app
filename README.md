# creat-react-app
### 安装必备工具Node.js
下载安装: 考虑到外网下载太慢, 可从http://npm.taobao.org/ 中的 https://npm.taobao.org/mirrors 下载

设定: 安装完毕后, 必须进行如下设定, 否则后续步骤会巨慢:

```bash
npm install -g cnpm --registry=https://registry.npm.taobao.org
npm config set registry https://registry.npm.taobao.org  
```

### 准备React
安装create-react-app命令
```bash
cnpm install -g create-react-app
```
使用create-react-app命令可快速构建 React 开发环境, 此项目是基于Webpack+ES6的
```bash
create-react-app my-app
cd my-app/
npm start
```
### 创建目录
在src目录下创建子目录js, css, images, 以及相应目录下的components

### 修改入口文件
修改index.html中的div的id属性为id="fly"(id名自取), 以匹配应用的名称.

修改index.js

### 开始创建组件
