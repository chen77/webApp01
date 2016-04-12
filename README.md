# webApp01
###2016.4.11 基本列表页布局

+ 布局一个基础页面，了解移动端布局流程[临摹](http://www.duanliang920.com/learn/web/html5/304.html);

###2016.4.12 事件添加

+ 修复图标模糊问题
```
  高清屏上需要两倍图片大小显示，引入两倍大的图标图片，用background-size制定显示大小
```
+ 了解zepto框架使用,添加切换事件,
```js
  var UA=window.navigator.userAgent;
	var Click="click";
  if(/ipad|iphone|android/.test(UA)){
				Click="tap";
			}
	oDiv[Click](function(){
	  //方便web端调试判断浏览器后用事件
	})
```
