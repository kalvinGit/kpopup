# kpopup
基于jQuery的轻量级滑出层插件，无需依赖任何Css文件

# 使用说明
···
// 右滑出层
new popup('#rightPopup', '#rightBtn', {
    // width: '334px',	// 滑出层宽度
    // height: '170px',	// 滑出层调度
    content: $('#content'),	// 主要内容；可以为html，可以为dom对象
    duration: 500	// 滑出速度，默认fast
}).popupRight();	// 可以调用setTop,setRight等方法对滑出层位置进行调整
···
