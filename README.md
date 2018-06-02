# css3
## css3背景图像区域
### background-clip属性
    background-clip属性指定背景绘制区域
    语法：background-clip:border-box|padding-box|content-box
### background-origin属性
    background-origin属性指定background-position属性应该时相对位置
    语法：background-origin:border-box|padding-box|content-box
### background-attachment属性
background-attachment属性指定图片是否滚屏
语法：background-origin:border-box|padding-box|content-box
### background-size属性
    background-size属性指定北京图片大小
    background-size:length|percentage|cover|contain
### css3 允许您为元素使用多个背景图像
    background-image:url(ima1.jpg),url(img2.png)
### 背景缩写属性可以在一个声明中设置所有的背景属性
    background:color position size repeat origin clip attachment image; 
## 渐变
### 线性（liner gradients）渐变属性
    是沿着一根轴线改变颜色，从起点到终点颜色进行顺序渐变（从一边拉向宁一边）
    语法：background:liner-gradient(direction,color-stop1,color-stop2)
    
    background:-webkit-liner-gradient(left,color-stop1,color-stop2)写开始点方向
    background:-moz-liner-gradient(right,color-stop1,color-stop2)写结束点方向
    background:-o-liner-gradient(right,color-stop1,color-stop2)写结束点方向
    background:liner-gradient(to right,color-stop1,color-stop2)写结束点方向
    
    
