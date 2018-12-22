<!--
 * @Author: Fred
 * @Date: 2018-12-22 15:14:55
 * @LastEditors: Fred
 * @LastEditTime: 2018-12-22 15:22:44
 * @Description: 
 -->
# 搭建parcel

```
1. npm init  -y                                         用来初始化生成一个新的 package.json 文件  -y（代表yes），则跳过提问阶段，直接生成一个新的 package.json 文件。
2.cnpm i parcel-bundler -S                              安装parcel
3.新建index.html和index.js


```
## 配置package.json

```
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "start": "parcel index.html",
}
```
## 打包项目
```
1.npm start
2.打开http://localhost:1234

```
##运行项目
1.克隆项目：git@github.com:fan-dong/parceljs.git
2.安装依赖：cnpm i 
3.运行项目：npm start
4.打开项目：http://localhost:1234