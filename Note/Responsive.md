<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/
TR/html4/loose.dtd">
如今在HTML5 中，则化繁为简：
<!DOCTYPE html>
如前所述，我写页面的时候从来不会手工敲出文档类型声明，我猜你也不会。——那你
嚷嚷半天有什么实际意义？ 不要着急，还得往页面中链接JavaScript 或CSS 文件呢。在
HTML 4.01 中，链接一个脚本文件的正确方法如下：
<script src="js/jquery-1.6.2.js" type="text/javascript"></script>
HTML5 中变得更简单：
<script src="js/jquery-1.6.2.js"></script>
如
（http://www.csszengarden.com）
CSS 禅意花园”（http://www.csszengarden.com）

http://demo.marcofolio.net/ 大量CSS动画DEMO

http://designlovr.com/ DEMO
重置样式一般会被加入到主样式文件的开头，用来将
各个浏览器的自有默认样式重置成统一表现，确保样式表中后续追加的
样式在不同浏览器中有相同的显示效果
normalize.css

user-scalable=no 即是禁止缩放。
name="viewport"属
性不言而喻。content="initial-scale=2.0 的意思是将页面放大两倍（同理，0.5 表
示缩小一半，3.0 表示放大3 倍），同时width=device-width 告诉浏览器页面的宽度应
该等于设备宽度

使用百分比和EM组合
在所有浏览器的解决方案中，设置 <body>元素的默认字体大小的是百分比：
实例
body {font-size:100%;}
h1 {font-size:2.5em;}
h2 {font-size:1.875em;}
p {font-size:0.875em;}


弹性图片
在现代浏览器（包括IE 7+）中要实现图片随着流动布局相应缩放非常简单。只需在CSS
中作如下声明：
img {
max-width: 100%;
}

其他多媒体标签上。如：
img,object,video,embed {
max-width: 100%;
}

，删除宽度和高度属性

background-color: rgba(255, 255, 255, 0.8);
http://lea.verou.me/css3patterns/ 背景

https://css-tricks.com/ 讨论CSS技术