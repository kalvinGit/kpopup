# kpopup插件
基于jQuery的轻量级滑出层插件，无需依赖任何Css文件

# 使用说明

## 引入js
```
<script src="https://cdn.bootcss.com/jquery/3.4.1/jquery.min.js"></script>
<script src="js/kpopup.js"></script>
```
## 放置html容器
```
<!-- 滑出层核心容器 -->
<div id="rightPopup"></div>

<!-- 滑出层里面的内容块 -->
<div id="content" style="display: none;">
    我是滑出块内容。。</br>
    我是滑出块内容。。</br>
    我是滑出块内容。。</br>
    重要事，说三遍。。。
</div>

```

## 实例化滑出层

```
// 右滑出层
new popup('#rightPopup', '#rightBtn', {
    // width: '334px',	// 滑出层宽度
    // height: '170px',	// 滑出层调度
    content: $('#content'),	// 主要内容；可以为html，可以为dom对象
    duration: 500	// 滑出速度，默认fast
}).popupRight();	// 可以调用setTop,setRight等方法对滑出层位置进行调整
```

## 效果图
![滑出效果](https://github.com/kalvinGit/kpopup/blob/master/img/GIF.gif)

[Kalvin在线工具](https://tools.kalvinbg.cn)  
