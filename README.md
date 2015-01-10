# myecharts
单独调用一echarts的时候非常简单。具体做法如下：
- 准备工作：建立一个js子文件夹，将esl，echarts，pie，bar，map等各种js放入其中。在js文件夹外新建一个空的html文件。
- 首先，调用esl.js，它提供了echarts图片的载体。
- 其次，使用require方法调用echarts.js和具体使用的类型图的js（比如map.js）。
- 再次，输入需要输入的数据。

[效果](http://chengjun.github.io/cn/2015/01/myecharts/)

<iframe src="http://chengjun.github.io/cn/2015/01/myecharts/" scrolling="no" width="600" ></iframe>

