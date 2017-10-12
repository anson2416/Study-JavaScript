# Study-JavaScript

## 001 - JS打气球例子

*2017-10-10*

`js-balloon.html` 主文件

参考b站上的视频例子拷贝/学习的代码。
代码实现的功能有：

 - 利用Javascript生成一定数量的气球（气球通过CSS画出来）
 - 气球以不同的速度网上升
 - 点击气球，气球会“爆炸”（跑远+变小）

#### 参考链接
[月薪4万的程序员有多强按？半小时原生JS开发打气球游戏，征服现场数万人!](https://www.bilibili.com/video/av15152538/index_1.html#page=1)

---
## 002 - JS飘落的爱心

*2017-10-11*

`JS-飘落的爱心.html` 主文件

`js/jquery-3.2.1.slim.min.js` Jquery瘦身版

`js/snowfall.jquery.min.js` Jquery插件-雪花飘落


参考b站上的视频例子拷贝/学习的代码。
代码实现的功能有：

 - 利用CSS的伪元素（::before  ::after）绘制一个心形图像♥
 - 调用Jquery插件Snowfall实现爱心从上往下飘落的效果

### Preview/Demo
![GIF飘落的爱心](https://github.com/anson2416/Study-JavaScript/blob/master/002%20-%20JS%E9%A3%98%E8%90%BD%E7%9A%84%E7%88%B1%E5%BF%83/demo/20171012100901SnowfallFlakes.gif)

### Notes

* 使用Jquery插件Snowfall的时候，记得添加下面的代码来解决窗口大小改变的时候，雪花会变成一行的问题。

  该问题在 (Position error #38)[https://github.com/loktar00/JQuery-Snowfall/issues/38] 有提及。

  `html,body{padding:0; margin:0; min-height: 100%; height:100%;}`

#### 参考链接

 - [程序员写爱心飘落特效去求婚，你们猜能坚持几个回合！](https://www.bilibili.com/video/av11913500/index_1.html#page=1)
 - [一步一步教你用CSS画爱心](http://www.cnblogs.com/yingzi1028/p/6248937.html)
 - [利用snowfall.jquery.js实现爱心满屏飞](http://www.cnblogs.com/yingzi1028/p/6249767.html)

---

> Written with [StackEdit](https://stackedit.io/).
