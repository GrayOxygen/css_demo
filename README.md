# css_demo
css练习demo

> 本工程为jquery的练习，一是复习基础的知识，二是给便于以后快速查阅


- position_absolute.html  效果如下图：
![绝对定位例子](https://github.com/GrayOxygen/jquery_demo/blob/master/%E5%AE%9A%E4%BD%8D/position_absolute_%E6%BC%94%E7%A4%BA%E5%9B%BE.png "绝对定位")

右边的时间是绝对定位，没设置top right bottom left这四个属性，所以会紧跟兄弟元素，但是不会影响常规流中的任何元素。上面每行li的内容自动分行，然后overflow设置为hidden，设置下右边时间的padding-left就行了

- position_z-index.html   效果如下图：
![z-index例子](https://github.com/GrayOxygen/jquery_demo/blob/master/%E5%AE%9A%E4%BD%8D/position_z-index_%E6%BC%94%E7%A4%BA%E5%9B%BE.png "z-index例子")

演示了都是absolute或者都是relative以及三个分别为relative、absolute、fixed的定位的div设置z-index示例
