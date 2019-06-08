# VanGot

这是一款处理原图还原轮廓，并加以创作的小程序。

### 前端

基于微信小程序，运用深搜及广搜算法对图像进行处理及操作。

### 后端

基于Express 框架 +  Mysql + opencv ，调用opencv API处理前端请求图片并返回黑白轮廓图片

**环境**

CentOS release 6.10

gcc (GCC) 6.1.0

Python 2.7.15

mysql  Ver 14.14 Distrib 5.6.44

> Note:  以上环境主要影响Mysql与opencv4nodejs库的安装
>
> ​			关于安装opencv4nodejs，更详细安装信息浏览[npm opencv4nodejs](<https://www.npmjs.com/package/opencv4nodejs>)

**脚本**

`npm run serve` windows线下测试

`npm run dev` linux线上部署

