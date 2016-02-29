1.主要基于现有的项目，实现数据维护界面中数据库数据表的图形展示
2.同时利用Jquery+javascript实现数据的拖拽功能
3.显示样式主要借助Bootstraps+css方式进行自定义
4.数据后台采用C#读取后台数据库中存放的数据表字段定义数据，通过JSon格式进行传输。json定义格式如下：
[
['GeoBasic','01_井位基础数据表(GeoBasic)',['井名(Well)','varchar(50)','区块(Block)','varchar(50)']],
['GEO_Skew','02_井斜数据表(GEO_Skew)',['井名(Well)','varchar(50)','批次(GroupID)','float']]
]

目前存在的bug：拖拽时，鼠标定位目前不太准确，正在解决中...