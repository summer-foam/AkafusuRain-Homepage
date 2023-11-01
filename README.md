# AkafusuRain-Homepage
 A customizable homepage template based on Vue.
这是一个基于 Vue 3 且可自定义的个人主页，如果喜欢记得点上一个 star   

![开源协议](https://img.shields.io/github/license/summer-foam/AkafusuRain-Homepage)
![框架](https://img.shields.io/badge/framework-Vue%203-3fb984)
  
## 💻 自定义 & 网页生成
1. 确保你的电脑上安装了 NodeJS（版本为 16+）和 git。
2. 将本库 `clone` 到本地。**（一定不要下载 zip，否则会导致无法构建！）**
```shell
git clone https://github.com/summer-foam/AkafusuRain-Homepage
```
3. 安装 Yarn
```shell
npm install yarn -g
```
4. 安装依赖库
```shell
yarn add @vue/cli -g
cd /path/to/crash-homepage
yarn set version berry
yarn install
```
5. 修改 `/config/config.js` 中的站点数据为你网站的数据。你可以直接像写对象一样写在大括号里边，亦可使用 import 引入。
6. 启动开发环境，在开发服务器中预览并编辑站点。
```shell
yarn serve
```
7. 推出开发环境并启动生产环境，生成静态页面。
```shell
yarn build
```
8. 在 `/dist` 中查收打包好的页面
