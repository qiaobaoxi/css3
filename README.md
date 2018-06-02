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
### 对角    
    background:-webkit-liner-gradient(left top,color-stop1,color-stop2)写开始点方向
    background:-moz-liner-gradient(right bottom,color-stop1,color-stop2)写结束点方向
    background:-o-liner-gradient(right bottom,color-stop1,color-stop2)写结束点方向
    background:liner-gradient(to right bottom,color-stop1,color-stop2)写结束点方向
    
    background:liner-gradient(30deg,color-stop1,color-stop2)
    
    background:liner-gradient(30deg,color-stop1 width,color-stop2 width)
### 线性渐变-重复渐变
    语法:background:repeating-linear-gradient(color1 length|percentage,color2 length|percentage)
### 径向渐变（radial gradients）属性
    background:radial-gradient(center,shape size,start-color,...,last-color)
### 形状说明
    circle-圆形
    ellipse-椭圆
    background:radial-gradient(circle,start-color,...,last-color)
### 尺寸大小关键字
    background:radial-gradient(size,start-color,...,last-color)
### 关键字说明
    closet-side:最近边   farhest-side:最远边
    closet-side:最近角   farhest-corner:最远角
