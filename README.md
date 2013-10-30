arScroll
========
插件功能：
1、图片自动滚动。可设定自动或者手动滚动
2、自动滚动时，当到达滚动体的边沿时，会自动反方向滚动
3、支持显示区域图片个数设定
4、支持每次滚动图片个数设定
5、支持滚动速度设定。快慢由你定
6、支持mouseover停止滚动，mouseout恢复滚动
7、前后手动按钮显示与否设定
8、支持水平垂直方向滚动自由设定
9、自定义html结构
10、支持页码显示
11、支持当前高亮显示，鼠标点击时高亮并自动滚动一张图片

历史版本：
=====================================
*   v1.3.3 [2013.05.10]
    1.整理优化代码,使之更直观,速度更快
    2.删除以页码为单位滚动方式
    3.优化点击高亮实现方法
    4.修复自动滚动到末页后点击next按钮还继续滚动的bug
    5.修复网速慢时显示区域尺寸设置错误的bug
*  ===========================
*   v1.3.1 [2012.09.10]
    1.可显示页码（可用于轮播广告）
    2.可自由设置html结构（默认为dl/dt/dd结构）
    3.高亮显示当前对象与相应页码
    4.精简代码
    5.修复已知bug
*  ===========================
*   v1.2.1 [2012.05.22]
    1.实现水平垂直方向滚动自由设定
    2.优化代码
*  ===========================
*   v1.1.1 [2012.02.02]
    1、添加滚动行数参数（PS:需在CSS中定义显示区域的高度）
*  ===========================
*   v1.0.1 [2011.12.02]
    1、图片自动滚动。可设定自动或者手动滚动
    2、自动滚动时，当到达滚动体的边沿时，会自动反方向滚动
    3、支持显示区域图片个数设定（这跟显示区域的宽度有关）
    4、支持每次滚动图片个数设定（默认为单个图片滚动），支持以页码为单位滚动
    5、支持滚动速度设定。快慢由你定
    6、支持mouseover停止滚动，mouseout恢复滚动
    7、前后手动按钮显示与否设定（PS:手动按钮滚动单位始终与页码为单位）
=====================================================================
/*
 *   jquery.arScroll.js
 *   power by Aaron 
 *   Aaron.xiexie@gmail.com
 *   2012.02.02
 */
=====================================================================
