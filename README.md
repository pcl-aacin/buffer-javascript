<h1 align="center">Buffer-JavaScript</h1>
<p align="center">
  <em>Buffer running autonomously in browser</em>
</p>
<p align="center">
  
![Github Stars](https://img.shields.io/github/stars/pcl-aacin/buffer-javascript.svg)
![license](https://img.shields.io/badge/LICENSE-GNU--3.0-brightgreen)
![Author](https://img.shields.io/badge/Author-pcl--aacin-green)
</p>

## Implementation principle
Its source code comes from [feross/buffer](https://github.com/feross/buffer), I modified it and imported [feross/ieee754](https://github.com/feross/ieee754) and [beatgammit/base64-js](https://github.com/beatgammit/base64-js) to make it run in the browser. Its underlying storage is based on Uint8Array/ArrayBuffer.

## Usage method
[feross/buffer](https://github.com/feross/buffer) is originally from nodejs' buffer library, so its use method is almost the same as that of nodejs' buffer library, so you can go to the [official document](https://nodejs.org/docs/latest/api/buffer.html) to check the usage
