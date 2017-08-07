# 一个监控多次点击事件的jquery插件
## 使用方法

1. 第一步引入本插件的js文件,需要和jQuery一起引用。

```
<script src="js/jquery/3.2.1/jquery.js"></script>
<script src="./mClick.js"></script>
```	
2.使用`.mClick()`调用插件

```
$('.btn').mClick(800, 3, function(){
	console.log('被点击了3次');
});
	
```
其中第一个参数是两次点击时间得最大间隔时间，第二个参数是点击几次调用回调函数，第三个参数是完成一次多次点击后执行的回调函数。

使用示例：[multipleClick.html](http://htmlpreview.github.io/?https://github.com/SmartDoubleXiao/multipleClick/blob/master/multipleClick.html)


