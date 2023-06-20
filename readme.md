# Metal学习

主要参考苹果官方文档，做个笔记

## Metal介绍

通过 Metal框架可以直接访问设备的图形处理单元（GPU），应用程序可以利用GPU快速渲染复杂场景并运行计算任务。

基于Metal的框架包含：MetalFX、MetalKit、MetalPerformaceShaders；

* MetalFX：比原生渲染效率更高；
* MetalKit：简化了屏幕上显示Metal内容的任务
* Metal Performance Shaders：提供了一个大型的优化计算和渲染着色器库，可以利用每个GPU的独特硬件。

## MSL

即着色器语言，全称 `Metal Shading Language`，是 C++的变体，通过 `MSL` 可以将方法运行到 `GPU` 上，着色器代码文件后缀为 `.metal`。

## 官方示例

### 1、计算两个长度一致的浮点型数组，按位相加的结果存放到第三个数组里。
[详情 > ](Contents/1.md)
