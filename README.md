    CSS3动画
    今日主打
    CSS3 动画
    CSS3 animation
    CSS3 @keyframes
    CSS3 will-change
    CSS3 动画
    动画（animation）
    anima——灵魂、animate——赋予生命
    动画可以定义为使用绘画的手法，创造生命运动的艺术。
    视觉暂留原理
    人类具有“视觉暂留”的特性，人的眼睛看到一幅画或一个物体后，在0.34秒内不会
    消失。
    动画原理
    通过把人物的表情、动作、变化等分解后画成许多动作瞬间的画幅，利用视觉暂留的
    原理，在一幅画还没有消失前播放下一幅画，就会给人造成一种流畅的视觉变化效果。
    兼容性
    IE10+、FireFox16+、Chrome43+、Safari9+、Opera30+、Android（-webkit-）
    CSS3 动画
    CSS3 动画
    使元素从一种样式逐渐变化为另一种样式的效果。
    CSS3 animation
    animation-name属性
    检索或设置对象所应用的动画名称。
    语法
    animation-name: keyframename | none;
    参数说明
    keyframename：指定要绑定到选择器的关键帧的名称；
    none：指定有没有动画（可用于覆盖从级联的动画）。
    CSS3 animation
    animation-duration属性
    检索或设置对象动画的持续时间
    语法
    animation-duration: time;
    参数说明
    time指定动画播放完成花费的时间。默认值为 0，意味着没有动画效果
    CSS3 animation
    animation-timing-function属性
    检索或设置对象动画的过渡类型
    语法
    animation-timing-function:
    ease | linear | ease-in | ease-out | ease-in-out | step-start | step-end |
    steps(<integer>[, [ start | end ] ]?) | cubic-bezier(<number>, <number>,
    <number>, <number>);
    CSS3 animation
    参数说明
    linear：线性过渡。等同于贝塞尔曲线(0.0, 0.0, 1.0, 1.0)
    ease：平滑过渡。等同于贝塞尔曲线(0.25, 0.1, 0.25, 1.0)
    ease-in：由慢到快。等同于贝塞尔曲线(0.42, 0, 1.0, 1.0)
    ease-out：由快到慢。等同于贝塞尔曲线(0, 0, 0.58, 1.0)
    ease-in-out：由慢到快再到慢。等同于贝塞尔曲线(0.42, 0, 0.58, 1.0)
    step-start：等同于 steps(1, start)
    step-end：等同于 steps(1, end)
    steps(<integer>[, [ start | end ] ]?)：接受两个参数的步进函数。第一个参数必须为正整数，指定函数的
    步数。第二个参数取值可以是start或end，指定每一步的值发生变化的时间点。第二个参数是可选的，默认
    值为end。
    cubic-bezier(<number>, <number>, <number>, <number>)：特定的贝塞尔曲线类型，4个数值需
    在[0, 1]区间内
    CSS3 animation
    animation-delay属性
    检索或设置对象动画的延迟时间。
    语法
    animation-delay: time;
    参数说明
    可选。定义动画开始前等待的时间，以秒或毫秒计。默认值为0。
    CSS3 animation
    animation-iteration-count属性
    检索或设置对象动画的循环次数。
    语法
    animation-iteration-count: infinite | <number>;
    参数说明
    <number>为数字，其默认值为“1”；infinite为无限次数循环。
    CSS3 animation
    animation-direction属性
    检索或设置对象动画在循环中是否反向运动。
    语法
    animation-direction: normal | reverse | alternate | alternate-reverse | initial | inherit;
    参数说明
    normal：正常方向；
    reverse：反方向运行；
    alternate：动画先正常运行再反方向运行，并持续交替运行；
    alternate-reverse：动画先反运行再正方向运行，并持续交替运行。
    CSS3 animation
    animation-fill-mode属性
    规定当动画不播放时（当动画完成或当动画有延迟未开始播放时），要应用到元素的样式。
    语法
    animation-fill-mode: none | forwards | backwards | both | initial | inherit;
    参数说明
    none：默认值。不设置对象动画之外的状态；
    forwards：设置对象状态为动画结束时的状态；
    backwards：设置对象状态为动画开始时的状态；
    both：设置对象状态为动画结束或开始的状态。
    CSS3 animation
    animation-play-state属性
    指定动画是否正在运行或已暂停。
    语法
    animation-play-state: paused | running;
    参数说明
    paused：指定暂停动画；
    running：默认值，指定正在运行的动画。
    CSS3 animation
    animation属性
    复合属性。检索或设置对象所应用的动画特效。
    语法
    animation: name duration timing-function delay iteration-count
    direction fill-mode play-state;
    举个栗子
    CSS3 @keyframes
    Keyframes定义
    关键帧，可以指定任何顺序排列来决定Animation动画变化的关键位置。
    使用说明
    使用@keyframes规则创建动画，通过逐步改变从一个CSS样式设定到另一个。
    在动画过程中可以通过@keyframes规则多次更改CSS样式的设定。
    CSS3 @keyframes
    语法
    @keyframes animationname {
    keyframes-selector {
    css-styles;
    }
    }
    参数说明
    animationname：必写项，定义animation的名称。
    keyframes-selector：必写项，动画持续时间的百分比，0-100%、from (0%)、to (100%)
    css-styles：必写项，一个或多个合法的CSS样式属性。
    CSS3 will-change
    目标
    增强页面渲染性能。
    CPU和GPU
    CPU即中央处理器，解释计算机指令以及处理计算机软件中的数据。
    GPU即图形处理器，专门处理和绘制图形相关的硬件。GPU是专为执行复杂的数学和几
    何计算而设计的，有了它，CPU就从图形处理的任务中解放出来，可以执行其他更多的
    系统任务。
    硬件加速
    在计算机中把计算量非常大的工作分配给专门的硬件来处理，减轻CPU的工作量。
    CSS3 will-change
    现状
    CSS的动画、变形、渐变并不会自动的触发GPU加速，而是使用浏览器稍慢的软件渲
    染引擎。
    在transition，transform和animation的世界里，应该卸载进程到GPU以加快速度。
    只有3D变形会有自己的layer，2D变形不会。
    translateZ() (or translate3d()) Hack
    为元素添加没有变化的3D变形，骗取浏览器触发硬件加速。
    代价
    这种情况通过向它自己的层叠加元素，占用RAM和GPU存储空间。
    CSS3 will-change
    will-change
    提前通知浏览器元素将要做什么动画，让浏览器提前准备合适的优化设置。
    语法
    will-change: auto|scroll-position|contents|<custom-ident>|<animateable-feature>;
    兼容性
    IE13+、FireFox47+、Chrome49+、Safari9.1+、Opera39+、IOS9.3+、Android52+
    CSS3 will-change
    关键词说明
    auto：此关键字表示没有特定的意图，适用于它通常所做的任何启发式和优化。
    scroll-position：表示将要改变元素的滚动位置。
    contents：表示将要改变元素的内容。
    <custom-ident>：明确指定将要改变的属性与给定的名称。
    <animateable-feature>：可动画的一些特征值，比如left、top、margin等。
    举个栗子
    使用注意（勿滥用、提前申明、remove）
    
    CSS3边框与圆角
    今日主打
    CSS3 圆角
    CSS3 盒阴影
    CSS3 边界图片
    CSS3 圆角
    border-radius 属性
    一个最多可指定四个border -*- radius属性的复合属性，这个属性允许你为元素添加圆角边框！
    语法
    border-radius: 1-4 length|% / 1-4 length|%;
    兼容性
    IE9+、FireFox4+、Chrome、Safari5+、Opera
    举个栗子
    CSS3 指定每个圆角
    多值
    四个值: 第一个值为左上角，第二个值为右上角，第三个值为右下角，第四个值为左下角。
    三个值: 第一个值为左上角, 第二个值为右上角和左下角，第三个值为右下角
    两个值: 第一个值为左上角与右下角，第二个值为右上角与左下角
    一个值： 四个圆角值相同
    属性
    border-top-left-radius 定义了左上角的弧度
    border-top-right-radius 定义了右上角的弧度
    border-bottom-right-radius 定义了右下角的弧度
    border-bottom-left-radius 定义了左下角的弧度
    CSS3 盒阴影
    box-shadow 属性
    box-shadow属性可以设置一个或多个下拉阴影的框
    语法
    box-shadow: h-shadow v-shadow blur spread color inset;
    兼容性
    IE9+、FireFox4+、Chrome、Safari5+、Opera
    举个栗子
    CSS3 边界图片
    border-image 属性
    使用border-image-*属性来构建美丽的可扩展按钮
    语法
    border-image: source slice width outset repeat;
    兼容性
    IE不兼容、FireFox、Chrome、Safari6+、Opera不兼容
    举个栗子
    CSS3 边界图片详解
    border-image-source 属性
    border-image-source属性指定要使用的图像，而不是由border-style属性设置的边框样式
    语法
    border-image-source: none|image;
    CSS3 边界图片详解
    border-image-slice 属性
    border-image -slice属性指定图像的边界向内偏移
    语法
    border-image-slice: number|%|fill;
    CSS3 边界图片详解
    border-image-width 属性
    border-image -width属性指定图像边界的宽度
    语法
    border-image-width: number|%|auto;
    CSS3 边界图片详解
    border-image-outset 属性
    border-image-outset用于指定在边框外部绘制 border-image-area 的量
    语法
    border-image-outset: length|number;
    CSS3 边界图片详解
    border-image-repeat 属性
    该属性用于图像边界是否应重复（repeated）、拉伸（stretched）或铺满（rounded）
    语法
    border-image-repeat: stretch|repeat|round|initial|inherit;
    
    CSS3背景
    今日主打
    CSS3 背景图像区域
    CSS3 背景图像定位
    CSS3 背景图像大小
    CSS3 多重背景图像
    CSS3 背景属性整合
    CSS3 背景图像区域
    background-clip 属性
    background-clip属性指定背景绘制区域
    语法
    background-clip: border-box|padding-box|content-box;
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    CSS3 背景图像定位
    background-origin属性
    background-origin属性指定background-position属性应该是相对位置
    语法
    background-origin: padding-box|border-box|content-box;
    兼容性
    IE9+、FireFox4+、Chrome、Safari5+、Opera
    举个栗子
    CSS3 背景图像大小
    background-size属性
    background-size属性指定背景图片大小
    语法
    background-size: length|percentage|cover|contain;
    兼容性
    IE9+、FireFox4+、Chrome、Safari5+、Opera
    举个栗子
    CSS3 多重背景图像
    CSS3 允许您为元素使用多个背景图像
    语法
    background-image: url(img1.jpg), url(img2.png);
    举个栗子
    CSS3 背景属性整合
    背景缩写属性可以在一个声明中设置所有的背景属性
    语法
    background: color position size repeat origin clip attachment image;
    举个栗子
    CSS3渐变
    今日主打
    CSS3 渐变
    CSS3 线性渐变
    CSS3 径向渐变
    CSS3 渐变
    渐变（gradients）可以在两个或多个指定的颜色之间显示平稳的过渡
    兼容性
    IE Chrome FireFox Safari Opera
    10+ 26+ 16+ 6.1+ 12.1+
    10.0 –webkit- 3.6 –moz- 5.1 –webkit- 11.6 –o-
    CSS3 线性渐变
    线性渐变（Linear Gradients）属性
    是沿着一根轴线改变颜色，从起点到终点颜色进行顺序渐变（从一边拉向另
    一边）
    语法
    background: linear-gradient(direction, color-stop1, color-
    stop2, ...);
    举个栗子
    CSS3 线性渐变
    线性渐变 - 从上到下（默认）
    background: linear-gradient(color-stop1, color-stop2, ...);
    CSS3 线性渐变
    线性渐变 - 从左到右
    background: -webkit-linear-gradient( begin-direction, color-stop1, color-stop2, ...);
    background:  -moz-linear-gradient( end-direction, color-stop1, color-stop2, ...);
    background:  -o-linear-gradient( end-direction, color-stop1, color-stop2, ...);
    background:  linear-gradient(to end-direction, color-stop1, color-stop2, ...);
    CSS3 线性渐变
    线性渐变 – 对角
    background: -webkit-linear-gradient( begin-level begin-vertical,
    color-stop1, color-stop2, ...);
    background: -moz-linear-gradient( end-level end-vertical,
    color-stop1, color-stop2, ...);
    background: -o-linear-gradient( end-level end-vertical,
    color-stop1, color-stop2, ...);
    background: linear-gradient( to end-level end-vertical,
    color-stop1, color-stop2, ...);
    CSS3 线性渐变
    线性渐变 – 使用角度
    语法
    background: linear-gradient(angle, color-stop1, color-stop2, ...);
    角度说明
    角度是指水平线和渐变线之间的角度，逆时针方向计算。
    0deg 将创建一个从下到上的渐变，90deg 将创建一个从左到右的渐变。
    CSS3 线性渐变
    线性渐变 – 颜色结点
    语法
    background: linear-gradient( color1 length|percentage,
    color2 length|percentage,
    ...
    );
    CSS3 线性渐变
    线性渐变 – 重复渐变
    语法
    background: repeating-linear-gradient( color1 length|percentage,
    color2 length|percentage,
    ...
    );
    CSS3 径向渐变
    径向渐变（Radial Gradients）属性
    从起点到终点颜色从内到外进行圆形渐变（从中间向外拉）
    语法
    background: radial-gradient(center, shape size, start-
    color, ..., last-color );
    举个栗子
    CSS3 径向渐变
    径向渐变 - 颜色结点均匀分布（默认）
    background: radial-gradient(color-stop1, color-stop2, ...);
    CSS3 径向渐变
    径向渐变 - 颜色结点不均匀分布
    background: radial-gradient(color1 length|percentage,
    color2 length|percentage, ...);
    CSS3 径向渐变
    径向渐变 – 设置形状
    语法
    background: radial-gradient(shape, color-stop1, color-
    stop2, ...);
    形状说明
    circle —— 圆形
    ellipse —— 椭圆（默认）
    CSS3 径向渐变
    径向渐变 – 尺寸大小关键字
    语法
    background: radial-gradient(size, color-stop1, color-
    stop2, ...);
    关键字说明
    closest-side：最近边 farthest-side：最远边
    closest-corner：最近角 farthest-corner：最远角
    CSS3 径向渐变
    径向渐变 – 重复渐变
    语法
    background: repeating-radial-gradien ( color1 length|percentage,
    color2 length|percentage,
    ...
    );
    
    CSS3过渡
    CSS3 过渡
    过渡（Transition）
    − 允许css的属性值在一定的时间区间内平滑地过渡
    − 在鼠标单击、获得焦点、被点击或对元素任何改变中触发，
    并圆滑地以动画效果改变CSS的属性值。
    兼容性
    IE10+、FireFox16+、Chrome26+、Safari6.1+、Opera12.1+
    CSS3 transition属性
    transition-property属性
    − 检索或设置对象中的参与过渡的属性。
    CSS3 transition属性
    语法
    − transition-property: none | all | property;
    参数说明
    − none(没有属性改变)
    − all(所有属性改变)，默认值
    − property(元素属性名)
    CSS3 transition属性
    transition-duration属性
    − 检索或设置对象过渡的持续时间。
    语法
    − transition-duration: time;
    参数说明
    − 规定完成过渡效果需要花费的时间（以秒或毫秒计）
    − 默认值是 0
    CSS3 transition属性
    transition-timing-function属性
    − 检索或设置对象中过渡的动画类型。
    语法
    transition-timing-function: ease | linear | ease-in | ease-out | ease-in-out |
    step-start | step-end | steps(<integer>[, [ start | end ] ]?) |
    cubic-bezier(<number>, <number>, <number>, <number>);
    CSS3 transition属性
    参数说明
    − linear：线性过渡。等同于贝塞尔曲线(0.0, 0.0, 1.0, 1.0)
    − ease：平滑过渡。等同于贝塞尔曲线(0.25, 0.1, 0.25, 1.0)
    − ease-in：由慢到快。等同于贝塞尔曲线(0.42, 0, 1.0, 1.0)
    − ease-out：由快到慢。等同于贝塞尔曲线(0, 0, 0.58, 1.0)
    − ease-in-out：由慢到快再到慢。等同于贝塞尔曲线(0.42, 0, 0.58, 1.0)
    CSS3 transition属性
    参数说明
    − step-start：等同于 steps(1, start)
    − step-end：等同于steps(1, end)
    − steps(<integer>[, [ start | end ] ]?)：接受两个参数的步进函数
    第一个参数：必须为正整数，指定函数的步数
    第二个参数：取值可是start或end，指定每一步的值发生变化的时间点
    第二个参数：可选，默认值为end
    CSS3 transition属性
    参数说明
    − cubic-bezier(<number>, <number>, <number>, <number>)：
    特定的贝塞尔曲线类型，4个数值需在[0, 1]区间内
    CSS3 transition属性
    transition-delay属性
    − 检索或设置对象延迟过渡的时间
    语法
    − transition-delay: time;
    参数说明
    − 指定秒或毫秒数之前要等待切换效果开始
    − 默认值为0
    CSS3 transition属性
    transition属性
    − 复合属性，检索或设置对象变换时的过渡。
    语法
    − transition: property duration timing-function delay;
    
    CSS3选择器
    基本选择器
    回顾选择器
    通配符选择器、元素选择器、类选择器、ID选择器、后代选择器
    新增基本选择器
    子元素选择器、相邻兄弟元素选择器、通用兄弟选择器、群组选择器
    基本选择器——子元素选择器
    概念
    子元素选择器只能选择某元素的子元素
    语法格式
    父元素 > 子元素 （Father > Children）
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    基本选择器——相邻兄弟元素选择器
    概念
    相邻兄弟选择器可以选择紧接在另一元素后的元素，而且他们具有一个相同的父元素
    语法格式
    元素 + 兄弟相邻元素 （Eelement + Sibling）
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    基本选择器——通用兄弟选择器
    概念
    选择某元素后面的所有兄弟元素，而且他们具有一个相同的父元素
    语法格式
    元素 ~ 后面所有兄弟相邻元素 （Eelement ~ Siblings）
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    基本选择器——群组选择器
    概念
    群组选择器是将具有相同样式的元素分组在一起，每个选择器之间使用逗号“,”隔开
    语法格式
    元素1, 元素2, …, 元素n （Eelement1, Element2, …, Elementn）
    兼容性
    IE6+、FireFox、Chrome、Safari、Opera
    举个栗子
    属性选择器
    对带有指定属性的HTML 元素设置样式
    使用CSS3属性选择器，你可以只指定元素的某个属性，或者你还可以同时指定元素的某个属性和
    其对应的属性值。
    Element[attribute]
    概念
    为带有 attribute 属性的 Element 元素设置样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute=“value”]
    概念
    为 attribute=“value” 属性的 Element 元素设置样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute~=“value”]
    概念
    选择 attribute 属性包含单词 “value" 的元素，并设置其样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute^=“value”]
    概念
    设置 attribute 属性值以 "value" 开头的所有 Element 元素的样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute$=“value”]
    概念
    设置 attribute 属性值以 "value" 结尾的所有 Element 元素的样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute*=“value”]
    概念
    设置 attribute 属性值包含 "value" 的所有 Element 元素的样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element[attribute|=“value”]
    概念
    选择 attribute 属性值为 "value”或以 "value-" 开头的元素，并设置其样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    伪类选择器
    动态伪类
    锚点伪类、用户行为伪类
    UI元素状态伪类
    CSS3结构类
    否定选择器
    伪元素
    动态伪类
    这些伪类并不存在于HTML中，只有当用户和网站交互的时候才能体现出来
    锚点伪类
    :link, :visited
    动态伪类
    用户行为伪类
    :hover, :active, :focus
    概念
    我们把":enabled",":disabled",":checked"伪类称为UI元素状态伪类
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    UI元素状态伪类
    CSS3的:nth选择器
    我们把CSS3的:nth选择器也成为CSS3结构类
    选择方法：
    :first-child、:last-child、:nth-child()、:nth-last-child()、:nth-of-type()、
    :nth-last-of-type()、:first-of-type、:last-of-type、:only-child、:only-of-type、:empty
    CSS3结构类
    概念
    选择属于其父元素的首个子元素的每个 Element 元素，并为其设置样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element:first-child
    概念
    指定属于其父元素的最后一个子元素的 Element 元素的样式
    兼容性
    IE8+、FireFox、Chrome、Safari、Opera
    举个栗子
    Element:last-child
    概念
    :nth-child(N) 选择器匹配属于其父元素的第 N 个子元素，不论元素的类型
    Element:nth-child(N)
    兼容性
    IE9+、FireFox4+、Chrome、Safari、Opera
    举个栗子
    Element:nth-child(number)
    选择某元素下的第number个Element元素
    关于参数(N)
    Element:nth-child(n)
    n是一个简单表达式，取值从“0”开始计算。这里只能是“n”，不能用其他字母代替。
    Element:nth-child(odd)、Element:nth-child(even)
    odd和even是可用于匹配下标是奇数或偶数的Element元素的关键词（第一个的下标是 1）
    概念
    匹配属于其元素的第 N 个子元素的每个元素，不论元素的类型，从最后一个子元素开始计数
    Element:nth-last-child(N)
    兼容性
    IE9+、FireFox4+、Chrome、Safari、Opera
    举个栗子
    概念
    :nth-of-type(N)选择器匹配属于父元素的特定类型的第 N 个子元素的每个元素
    Element:nth-of-type(N)
    兼容性
    IE9+、FireFox4+、Chrome、Safari、Opera
    举个栗子
    概念
    匹配属于父元素的特定类型的第 N 个子元素的每个元素，从最后一个子元素开始计数
    Element:nth-last-of-type(N)
    兼容性
    IE9+、FireFox4+、Chrome、Safari、Opera
    举个栗子
    概念
    :first-of-type 选择器匹配属于其父元素的特定类型的首个子元素的每个元素
    Element:first-of-type
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    概念
    :last-of-type 选择器匹配属于其父元素的特定类型的最后一个子元素的每个元素
    Element:last-of-type
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    概念
    :only-child 选择器匹配属于其父元素的唯一子元素的每个元素
    Element:only-child
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    概念
    :only-of-type 选择器匹配属于其父元素的特定类型的唯一子元素的每个元素
    Element:only-of-type
    兼容性
    IE9+、FireFox4+、Chrome、Safari、Opera
    举个栗子
    概念
    :empty 选择器匹配没有子元素（包括文本节点）的每个元素
    Element:empty
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    否定选择器（:not）
    概念
    :not(Element/selector) 选择器匹配非指定元素/选择器的每个元素
    语法格式
    父元素:not(子元素/子选择器) （Father:not(Children/selector)）
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    举个栗子
    伪元素
    CSS 伪元素用于向某些选择器设置特殊效果
    语法格式
    元素::伪元素 （Element::pseudo-element）
    兼容性
    IE9+、FireFox、Chrome、Safari、Opera
    概念
    根据 "first-line" 伪元素中的样式对 Element 元素的第一行文本进行格式化
    伪元素——Element::first-line
    说明
    "first-line" 伪元素只能用于块级元素
    举个栗子
    概念
    用于向文本的首字母设置特殊样式
    伪元素——Element::first-letter
    说明
    "first-letter" 伪元素只能用于块级元素
    举个栗子
    概念
    在元素的内容前面插入新内容
    伪元素——Element::before
    说明
    常用"content"配合使用
    举个栗子
    概念
    在元素的内容后面插入新内容
    伪元素——Element::after
    说明
    常用“content”配合使用，多用于清除浮动
    举个栗子
    概念
    用于设置在浏览器中选中文本后的背景色与前景色
    伪元素——Element::selection
    兼容性说明
    ::selection在IE家族中，只有IE9+版本支持，在Firefox中需要加上其前缀“-moz”
    举个栗子
    什么是权重
    当很多的规则被应用到某一个元素上时，权重是一个决定哪种规则生效，或者是优先级的过程
    CSS权重
    权重等级与权值
    行内样式(1000)>ID选择器(100)>类、属性选择器和伪类选择器(10)>元素和伪元素(1)>*(0)
    权重计算口诀
    从0开始，一个行内样式+1000，一个id+100，一个属性选择器、class或者伪类+10，一个元
    素名或者伪元素+1
    包含更高权重选择器的一条规则拥有更高的权重
    ID选择器(#idValue)的权重比属性选择器([id="idValue"])高
    带有上下文关系的选择器比单纯的元素选择器权重要高
    与元素“挨得近”的规则生效
    最后定义的这条规则会覆盖上面与之冲突的规则
    CSS权重规则
    无论多少个元素组成的选择器，都没有一个class选择器权重高
    通配符选择器权重是0，被继承的css属性也带有权重，权重也是0
    
    常见的 CSS3 选择器
    选择器  例子  例子描述  CSS
    . class .intro  选择 class="intro" 的所有元素。  1
    # id #firstname  选择 id="firstname" 的所有元素。  1
    * *  选择所有元素。  2
    element p  选择所有 <p> 元素。  1
    element , element div,p  选择所有 <div> 元素和所有 <p> 元
    素。
    1
    element element div p  选择 <div> 元素内部的所有 <p> 元
    素。
    1
    element > element div>p  选择父元素为 <div> 元素的所有 <p>
    元素。
    2
    element + element div+p  选择紧接在 <div> 元素之后的所有 <p>
    元素。
    2
    [ attribute ] [target]  选择带有 target 属性所有元素。  2
    [ attribute = value ] [target=_blank]  选择 target="_blank" 的所有元素。  2
    [ attribute ~= value ] [title~=flower]  选择 title 属性包含单词 "flower" 的所有
    元素。
    2
    [ attribute |= value ] [lang|=en]  选择 lang 属性值以 "en" 开头的所有元
    素。
    2
    :link a:link  选择所有未被访问的链接。  1
    :visited a:visited  选择所有已被访问的链接。  1
    :active a:active  选择活动链接。  1
    :hover a:hover  选择鼠标指针位于其上的链接。  1
    :focus input:focus  选择获得焦点的 input 元素。  2
    :first-letter p:first-letter  选择每个 <p> 元素的首字母。  1
    :first-line p:first-line  选择每个 <p> 元素的首行。  1
    :first-child p:first-child  选择属于父元素的第一个子元素的每个
    <p> 元素。
    2
    :before p:before  在每个 <p> 元素的内容之前插入内容。  2
    :after p:after  在每个 <p> 元素的内容之后插入内容。  2
    :lang( language ) p:lang(it)  选择带有以 "it" 开头的 lang 属性值的每
    个 <p> 元素。
    2
    element1 ~ element2 p~ul  选择前面有 <p> 元素的每个 <ul> 元
    素。
    3
    [ attribute ^= value ] a[src^="https"]  选择其 src 属性值以 "https" 开头的每个
    <a> 元素。
    3
    [ attribute $= value ] a[src$=".pdf"]  选择其 src 属性以 ".pdf" 结尾的所有
    <a> 元素。
    3
    [ attribute *= value ] a[src*="abc"]  选择其 src 属性中包含 "abc" 子串的每
    个 <a> 元素。
    3
    :first-of-type p:first-of-type  选择属于其父元素的首个 <p> 元素的每
    个 <p> 元素。
    3
    :last-of-type p:last-of-type  选择属于其父元素的最后 <p> 元素的每
    个 <p> 元素。
    3
    :only-of-type p:only-of-type  选择属于其父元素唯一的 <p> 元素的每
    个 <p> 元素。
    3
    :only-child p:only-child  选择属于其父元素的唯一子元素的每个
    <p> 元素。
    3
    :nth-child( n ) p:nth-child(2)  选择属于其父元素的第二个子元素的每个
    <p> 元素。
    3
    :nth-last-child( n ) p:nth-last-
    child(2)
    同上，从最后一个子元素开始计数。  3
    :nth-of-type( n ) p:nth-of-type(2)  选择属于其父元素第二个 <p> 元素的每
    个 <p> 元素。
    3
    :nth-last-of-type( n ) p:nth-last-of-
    type(2)
    同上，但是从最后一个子元素开始计数。  3
    :last-child p:last-child  选择属于其父元素最后一个子元素每个
    <p> 元素。
    3
    :root :root  选择文档的根元素。  3
    :empty p:empty  选择没有子元素的每个 <p> 元素（包括
    文本节点）。
    3
    :target #news:target  选择当前活动的 #news 元素。  3
    :enabled input:enabled  选择每个启用的 <input> 元素。  3
    :disabled input:disabled  选择每个禁用的 <input> 元素  3
    :checked input:checked  选择每个被选中的 <input> 元素。  3
    :not( selector ) :not(p)  选择非 <p> 元素的每个元素。  3
    ::selection ::selection  选择被用户选取的元素部分。  3
    
    CSS3转换
    今日主打
    CSS3 Transform
    CSS3 2D转换
    CSS3 3D转换
    CSS3 Transform与坐标系统
    CSS3 矩阵
    CSS3 扩展属性
    CSS3 Transform
    CSS3的变形（Transform）属性
    让元素在一个坐标系统中变形。这个属性包含一系列变形函数，可以移动、旋转和缩放元素。
    语法
    transform ： none | <transform-function> [ <transform-function> ]*;
    兼容性
    IE12+、FireFox16+、Chrome36+、Safari16+、Opera23+
    默认值
    transform: none;
    CSS3 2D转换
    CSS3 rotate()
    CSS3 translate()
    CSS3 scale()
    CSS3 skew()
    CSS3 matrix()
    CSS3 2D转换
    旋转rotate
    通过指定的角度参数对原元素指定一个2D rotation（2D 旋转）。
    语法
    transform: rotate(<angle>);
    参数说明
    angle指旋转角度，正数表示顺时针旋转，负数表示逆时针旋转。
    举个栗子
    CSS3 2D转换
    移动translate
    translate()方法，根据左(X轴)和顶部(Y轴)位置给定的参数，从当前元素位置移动。
    三种情况
    translateX(x)仅水平方向移动（X轴移动）;
    translateY(Y)仅垂直方向移动（Y轴移动）;
    translate(x, y)水平方向和垂直方向同时移动（也就是X轴和Y轴同时移动）。
    CSS3 2D转换
    translateX(<translation-value>)
    通过给定一个X方向上的数目指定一个translation。
    语法
    transform: translateX(<translation-value>);
    举个栗子
    CSS3 2D转换
    translateY(<translation-value>)
    通过给定一个Y方向上的数目指定一个translation。
    语法
    transform: translateY(<translation-value>);
    举个栗子
    CSS3 2D转换
    translate(<translation-value>[, <translation-value>])
    通过矢量[tx, ty]指定一个2D translation, tx是第一个过渡值参数, ty是第二个过渡值参数选项。
    语法
    transform: translate(<translation-value>[, <translation-value>]);
    举个栗子
    CSS3 2D转换
    缩放scale
    scale()方法，指定对象的2D scale（2D缩放）。
    三种情况
    scaleX(x)元素仅水平方向缩放（X轴缩放）;
    scaleY(y)元素仅垂直方向缩放（Y轴缩放）;
    scale(x, y)使元素水平方向和垂直方向同时缩放（也就是X轴和Y轴同时缩放）。
    CSS3 2D转换
    scaleX(<number>)
    使用 [sx, 1] 缩放矢量执行缩放操作，sx为所需参数。
    语法
    transform: scaleX(<number>);
    举个栗子
    CSS3 2D转换
    scaleY(<number>)
    使用 [1, sy] 缩放矢量执行缩放操作，sy为所需参数。
    语法
    transform: scaleY(<number>);
    举个栗子
    CSS3 2D转换
    scale(<number>[, <number>])
    提供执行[sx,sy]缩放矢量的两个参数指定一个2D scale（2D缩放）。
    语法
    transform: scale(<number>[, <number>]);
    举个栗子
    CSS3 2D转换
    扭曲skew
    skew()方法，指定对象skew transformation（斜切扭曲）。
    三种情况
    skewX(x)仅使元素在水平方向扭曲变形（X轴扭曲变形）;
    skewY(y)仅使元素在垂直方向扭曲变形（Y轴扭曲变形）;
    skew(x, y)使元素在水平和垂直方向同时扭曲（X轴和Y轴同时按一定的角度值进行扭曲变形）。
    CSS3 2D转换
    skewX(<angle>)
    按给定的角度沿X轴指定一个skew transformation（斜切变换）。
    语法
    transform: skewX(<angle>);
    举个栗子
    CSS3 2D转换
    skewY(<angle>)
    按给定的角度沿Y轴指定一个skew transformation（斜切变换）。
    语法
    transform: skewY(<angle>);
    举个栗子
    CSS3 2D转换
    skew(<angle> [, <angle>])
    X轴Y轴上的skew transformation（斜切变换）。第一个参数对应X轴，第二个参数对应Y轴。
    语法
    transform: skew(<angle> [, <angle>]);
    举个栗子
    CSS3 2D转换
    矩阵matrix
    以一个含六值的(a,b,c,d,e,f)变换矩阵的形式指定一个2D变换。
    相当于直接应用一个[a,b,c,d,e,f]变换矩阵。
    语法
    transform: matrix(a, c, b, d, tx, ty);
    参数说明
    tx, ty就是就是基于X和Y坐标重新定位元素。
    CSS3 3D转换
    CSS3 rotate3d()
    CSS3 translate3d()
    CSS3 scale3d()
    CSS3 matrix3d()
    CSS3 3D转换
    旋转rotateX
    rotateX方法指定对象在x轴上的旋转角度。
    语法
    transform: rotateX(angle);
    参数说明
    angle表示旋转的角度。
    举个栗子
    CSS3 3D转换
    旋转rotateY
    rotateY方法指定对象在y轴上的旋转角度。
    语法
    transform: rotateY(angle);
    参数说明
    angle表示旋转的角度。
    举个栗子
    CSS3 3D转换
    旋转rotateZ
    rotateZ方法指定对象在z轴上的旋转角度。
    语法
    transform: rotateZ(angle);
    参数说明
    angle表示旋转的角度。
    举个栗子
    CSS3 3D转换
    旋转rotate3d
    rotate3d方法指定对象的3D旋转角度。
    语法
    transform: rotate3d(x, y, z, angle);
    参数说明
    前3个参数分别表示旋转的方向x,y,z，第4个参数表示旋转的角度，参数不允许省略。
    举个栗子
    CSS3 3D转换
    移动translateZ
    translateZ方法指定对象Z轴的平移。
    语法
    transform: translateZ(z);
    参数说明
    参数对应Z轴，不允许省略。
    举个栗子
    CSS3 3D转换
    移动translate3d
    translate3d方法指定对象的3D位移。
    语法
    transform: translate3d(x, y, z);
    参数说明
    第1个参数对应X轴，第2个参数对应Y轴，第3个参数对应Z轴，参数不允许省略。
    举个栗子
    CSS3 3D转换
    缩放scaleZ
    scaleZ方法指定对象的z轴缩放。
    语法
    transform: scaleZ(z);
    参数说明
    参数对应Z轴，不允许省略。
    举个栗子
    CSS3 3D转换
    缩放scale3d
    scale3d方法指定对象的3D缩放。
    语法
    transform: scale3d(x, y, z);
    参数说明
    第1个参数对应X轴，第2个参数对应Y轴，第3个参数对应Z轴，参数不允许省略。
    举个栗子
    CSS3 3D转换
    矩阵matrix3d
    matrix3d方法以一个4x4矩阵的形式指定一个3D变换。
    语法
    transform: matrix3d(sx, n, n, n, n, sy, n, n, n, n, sz, n, n, n, n, 1);
    参数说明
    使用 16 个值的 4 x 4 矩阵。
    CSS3 Transform与坐标系统
    transform-origin属性
    transform-origin属性允许您更改转换元素的位置。
    语法
    transform-origin: x-axis y-axis z-axis;
    举个栗子
    CSS3 矩阵
    矩阵的概念
    矩阵可以理解为方阵，只不过，平时方阵里面站的是人，矩阵中是数值。而所谓矩阵的计算，就
    是两个方阵的人（可以想象成古代的方阵士兵）相互冲杀。
    CSS3中的矩阵
    CSS3中的矩阵指的是一个方法，书写为matrix()和matrix3d()；
    matrix是元素2D平面的移动变换(transform)，2D变换矩阵为3*3；
    matrix3d是元素3D的移动变换(transform)，3D变换则是4*4的矩阵。
    CSS3 矩阵
    矩阵matrix
    transform: matrix(a, c, b, d, tx, ty);
    注意书写方向是竖直方向。
    转换公式
    x、y表示转换元素的所有坐标
    目标矩阵说明
    ax+cy+e为变换后的水平坐标，bx+dy+f表示变换后的垂直位置。
    CSS3 矩阵
    矩阵matrix举个栗子
    transform: matrix(1, 0, 0, 1, 30, 30); /* a=1, b=0, c=0, d=1, e=30, f=30 */
    根据这个矩阵偏移元素的中心点，假设是(0, 0)，即x = 0, y = 0
    变换后，x=ax+cy+e=1*0+0*0+30=30，y=bx+dy+f=0*0+0*1+30=30
    于是，整个元素的中心点从(0, 0)变成了(30, 30)，整个元素就发生了平移
    说明
    transform: matrix(1, 0, 0, 1, x, y)等同于transform: translate(x, y)。
    注意
    matrix在FF浏览器下需要添加单位，webkit内核默认px，translate等方法需要加单位。
    CSS3 矩阵
    矩阵matrix缩放(scale)
    matrix(sx, 0, 0, sy, 0, 0) —— scale(sx, sy)
    矩阵matrix旋转(rotate)
    matrix(cosθ, sinθ,-sinθ, cosθ, 0, 0) —— rotate(θdeg)。
    矩阵matrix拉伸(skew)
    matrix(1, tanθy, tanθx, 1, 0, 0) —— skew(θxdeg, θydeg)。
    CSS3 矩阵
    矩阵matrix镜像对称效果
    matrix((1-k*k) / (1+k*k), 2k / (1 + k*k), 2k / (1 + k*k), (k*k - 1) / (1+k*k), 0, 0)
    小小说明
    对称轴一定通过元素变换的中心点，k是对称轴的斜率
    举个栗子
    CSS3 矩阵
    3D变换中的矩阵
    从二维到三维，是从4到9；而在矩阵里头是从3*3变成4*4, 9到16了。
    小小例子
    transform: matrix3d(sx, 0, 0, 0, 0, sy, 0, 0, 0, 0, sz, 0, 0, 0, 0, 1);
    CSS3 扩展属性
    transform-style属性
    transform-style属性指定嵌套元素是怎样在三维空间中呈现。
    语法
    transform-style: flat|preserve-3d;
    举个栗子
    默认值
    transform-style: flat;
    CSS3 扩展属性
    perspective属性
    指定观察者与「z=0」平面的距离，使具有三维位置变换的元素产生透视效果。
    语法
    perspective: number|none;
    举个栗子
    默认值
    perspective: none;
    CSS3 扩展属性
    perspective-origin属性
    指定透视点的位置。
    语法
    perspective-origin: x-axis y-axis;
    举个栗子
    默认值
    perspective-origin: 50% 50%;
    CSS3 扩展属性
    backface-visibility属性
    指定元素背面面向用户时是否可见。
    语法
    backface-visibility: visible|hidden;
    举个栗子
    默认值
    backface-visibility: visible;
