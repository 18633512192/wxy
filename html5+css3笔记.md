# <center>html5+css3笔记

<hr>

### 一、html5笔记<br>

1、在html5的语法中，属性值不放在引号中也是正确的；<br>
2、在html5中，部分标志属性值可以省略；<br>
html5可以省略属性值的属性：<br>
checked、readonly、defer、ismap、<br>nohref、noshade、nowrap、selectad、<br>disabled、multiple、moresize；等；
3、音频标签：<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)、HTML5通过audio标签来解决音频播放的问题;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)、并且可以通过附加属性可以更友好控制音频的播放，如：<br>
<p>
    <ul>
        <li>autoplay 自动播放</li>
        <li>controls 是否显不默认播放控件</li>
        <li>loop 循环播放</li>
        <li>preload 预加载 同时设置autoplay时些属性失效</li>
    </ul>
</p>
4、视频标签；<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)、HTML5通过video标签来解决视频播放的问题；<br>
(2)、video标签附加属性：<br>
<p>
    <ul>
        <li>autoplay 自动播放</li>
        <li>controls 是否显示默认播放控件</li>
        <li>preload 预加载，同时设置了autoplay，此属性将失效</li>
        <li>width 设置播放窗口宽度</li>
        <li>height 设置播放窗口的高度</li>
    </ul>
</p>

### 二、css3笔记<br>

1、css3过渡属性：transition属性<br>
可以设置元素的过渡效果，当某个属性被设置成过渡属性之后，<br>这个属性的值如果发生变化，就会以动画的形式从初始状态过渡到结束状态；<br>
2、transition属性 分析：<br>
ransition: width 2s linear 0.5s;<br>
<ul>
    <li>第一个值是设置过渡属性;</li>
    <li>第二个值是设置过渡时间;</li>
    <li>第三个值是设置过渡函数，这个函数可以设置过渡效果<br>是以怎么样的方式运动，linear表示运输运动。</li>
    <li>第四个值表示延时时间，在上面的例子中，鼠标悬浮后经<br>过0.5秒后元素才开始运动。</li>
</ul>
过渡效果可以设置多个过渡属性<br>

4、css3动画效果；<br>
(1)、定义动画：<br>
通过@keyframes定义一个简单的动画，<br>
@keyframes用于创建动画；<br>
(2)、循环动画：<br>
infinite属性为不断循环；<br>
