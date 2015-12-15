# metro-tips
metro风格的小提示框，兼容各种浏览器

## 综述

* 版本：1.0.0
* 浏览器支持： 所有浏览器
* demo: [http://backtonaturedemo.github.io/frontend/demo/tips/tips.html](http://backtonaturedemo.github.io/frontend/demo/tips/tips.html)

![](http://comment.bjcnc.img.sohucs.com/pwULRS4.png)

## 安装

	<script src="/path/to/tips.js"></script>
	// 或者
	var Tips = require('tips.js');

## 使用方法

使用方法如下：

	Tips({
        theme: 'green',
        content: '成功',
        showTime: 1200,
        callback: function () {
            console.log(123);
        }
    });

## API说明

### 配置参数

`theme`: 主题，有green,blue,red三个主题

`content`: 提示内容

`showTime`: 展示时间

`callback`: 展示时间结束时执行的回调函数







