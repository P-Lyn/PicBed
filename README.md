# 用GitHub仓库做图床
---

## 创建库
* 网页端创建一个空的Public Repository
* 在本地创建库（文件夹），把图片放进去
* 将本地库PUSH到云端（点击download Repository获得库链接）

注意：每次PUSH都需要commit（不能是空白）；必须是公共库，因为私有库中图片的地址会通过改变token的值来实时改变

## 使用方法

* 在MD文件中使用（也可在GitHub网页端的MD文件中显示） --> 点击库中的图片，**点击download获得图片链接**，在MD中插入图片，如下：
https://raw.githubusercontent.com/P-Lyn/PICBED/master/chips_overview/FPGA_xcalibur5090.png
![](https://raw.githubusercontent.com/P-Lyn/PICBED/master/chips_overview/FPGA_xcalibur5090.png)


* 在GitHub网页端中显示（无法在MD文件中显示） --> 直接复制库中图片的地址，如下：
https://github.com/P-Lyn/PICBED/blob/master/chips_overview/FPGA_xcalibur5090.png
![](https://github.com/P-Lyn/PICBED/blob/master/chips_overview/FPGA_xcalibur5090.png)
