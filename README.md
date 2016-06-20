# jquery.nicescroll
Jquery滚动条插件
jquery.nicescroll.min.js滚动条使用方法,Nicescroll 是制作自定义滚动条的jq插件。支持div,iframe,html等使用,兼容IE7-8,safari,firefox,webkit内核浏览器(chrome,safari)以及智能终端设备浏览器的滚动条。

页面使用：

$("html").niceScroll({ <br>
	cursorcolor:"#E62020", <br>
	cursoropacitymax:1, <br>
	touchbehavior:false, <br>
	cursorwidth:"10px", <br>
	cursorborder:"0", <br>
	cursorborderradius:"5px"<br>

})

nicescroll详细参数配置：

cursorcolor - 设置滚动条颜色，默认值是“＃000000”<br>
cursoropacitymin - 滚动条透明度最小值<br>
cursoropacitymax - 滚动条透明度最大值<br>
cursorwidth - 滚动条的宽度像素，默认为5（你可以写“5PX”）<br>
cursorborder - CSS定义边框，默认为“1px solid #FFF”<br>
cursorborderradius - 滚动条的边框圆角<br>
ZIndex的 - 改变滚动条的DIV的z-index值，默认值是9999<br>
scrollspeed - 滚动速度，默认值是60<br>
mousescrollstep - 滚动鼠标滚轮的速度，默认值是40（像素）<br>
touchbehavior - 让滚动条能拖动滚动触摸设备默认为false<br>
hwacceleration - 使用硬件加速滚动支持时，默认为true<br>
boxzoom - 使变焦框的内容，默认为false<br>
dblclickzoom - （仅当boxzoom = TRUE）变焦启动时，双点击框，默认为true<br>
gesturezoom - boxzoom = true并使用触摸设备）变焦（仅当激活时，间距/盒，默认为true<br>
grabcursorenabled“抢”图标，显示div的touchbehavior = true时，默认值是true<br>
autohidemode，如何隐藏滚动条的作品，真正的默认/“光标”=只光标隐藏/ FALSE =不隐藏<br>
的背景下，改变铁路背景的CSS，默认值为“”<br>
iframeautoresize中，AUTORESIZE iframe上的load事件（默认：true）<br>
cursorminheight，设置最低滚动条高度（默认值：20）<br>
preservenativescrolling，您可以用鼠标滚动本地滚动的区域，鼓泡鼠标滚轮事件（默认：true）<br>
railoffset，您可以添加抵消顶部/左轨位置（默认：false）<br>
bouncescroll，使滚动反弹结束时的内容移动（仅硬件ACCELL）（默认：FALSE）<br>
spacebarenabled，允许使用空格键滚动（默认：true）<br>
railpadding，设置间距（默认：顶：0，右：0，左：0，底部：0}）<br>
disableoutline，Chrome浏览器，禁用纲要（橙色hightlight）时，选择一个div nicescroll（默认：true）<br>
