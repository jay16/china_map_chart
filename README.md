## china_map_chart

这是一个绘制中国34省地图的jquery插件.

### 实现原理

* 使用svg绘制地图
* 使用js,jquery操作svg对象

特点: **未使用图片，所有样式使用js,jquery实现**

### 功能

* 鼠标悬浮效果
* 鼠标点击效果
* 鼠标悬浮提示框效果

### 缺陷

* 点击到省名称时，鼠标点击效果未出现

原因: 地图绘制与名称绘制在两个层面，省名称层面位地图层面之上.


### 待添加功能:

* 传递点击事件，对点击省份事件自定义处理

### 使用向导

[实例演示](http://solife.us/jquery/china-map-chart)

实例代码:

    <script src="../src/jquery.js" type="text/javascript"></script>
    <script src="../src/china_map_chart.js" type="text/javascript"></script>
    
    <script>
    $(function(){ 
      $("#china_map_chart").china_map_chart();
    });
    </script>
    
    <div id="china_map_chart"></div>
    
## TODO

* 完善jquery插件功能
* 做成ruby gem插件

ps: 任何反馈或学习交流都可以联系我
