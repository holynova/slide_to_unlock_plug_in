
# jQuery 滑动解锁插件
## 下载
[github链接](https://github.com/holynova/slide_to_unlock_plug_in)
## 使用方法

1. 引入插件文件

```
<link rel="stylesheet" type="text/css" href="jquery.slide_to_unlock.css"> 
<script src='jquery.slide_to_unlock.js'></script>
```

2. 创建一个div,作为容器,比如```$container```
3. 在脚本中初始化

```
$container.slideToUnlock(options);
```
其中options为可选参数,有默认值
options参数列表
## 参数列表
|name|describe|default|
|------|------|------|
|width|width of the slider|width of container element|
|height|height of the slider|height of container element|
|bgColor|background color|#E8E8E8|
|progressColor|color of the progress bar|#FFE97F|
|handleColor|color of the handler|#fff|
|succColor|background color when successfully unlocked|#78D02E|
|text|text on the progress bar|'slide to unlock'|
|textColor|color of text|#000|
|succText|text on the progress bar when successfully unlocked|'ok!'|
|succTextColor|color of succText|#000|
|succFunc|callback function when success|```function() { alert('successfully unlock!'); }```|
## demo