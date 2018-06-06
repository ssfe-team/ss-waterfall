### Waterfall 瀑布流组件

#### 概述

元素可跨列显示的三列瀑布流布局组件。

### props
属性|说明|类型|必需|默认值
---|---|---|---|---
propData|要显示的数据(每项数据须有width和height)|Array|是|[]
propRatio|宽高比临界值，据此决定默认占几列，大于arr[1]占满，小于arr[0]占一列|Array|否|[2，3]
maxColNum|最大列数|Number|否|3
maxDiff|每列允许的最大空白高度|Number|否|50
minHeight|每个元素的最小高度|Number|否|18
boxRect|元素下、右 margin|Object|否|{bottom: 8, right: 8}
waterfallWidth|瀑布流宽度|Number|否|600