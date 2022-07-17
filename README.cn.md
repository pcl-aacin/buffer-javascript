<h1 align="center">Buffer-JavaScript</h1>
<p align="center">
  <em>在浏览器上运行的Buffer</em>
</p>
<p align="center">
  
![Github Stars](https://img.shields.io/github/stars/pcl-aacin/buffer-javascript.svg)
![license](https://img.shields.io/badge/LICENSE-GNU--3.0-brightgreen)
![Author](https://img.shields.io/badge/Author-pcl--aacin-green)
</p>

## 运行原理
它的源码来自[feross/buffer](https://github.com/feross/buffer)，我修改了它，并手动导入了[feross/ieee754](https://github.com/feross/ieee754)和[beatgammit/base64-js](https://github.com/beatgammit/base64-js)使该库可以直接被调用。它的底层存储基于Uint8Array/ArrayBuffer。

## 使用方法
[feross/buffer](https://github.com/feross/buffer)本就来自nodejs的Buffer库，所以它的使用方法与nodejs的Buffer库使用方法十分类似，所以你可以直接前往[官方文档](https://nodejs.org/docs/latest/api/buffer.html)来查看使用方法
