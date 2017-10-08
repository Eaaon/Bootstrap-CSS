# Bootstrap-CSS
[Bootstrap全局CSS样式学习](http://v3.bootcss.com/css/#overview)

设置全局 CSS 样式；基本的 HTML 元素均可以通过 class 设置样式并得到增强效果；还有先进的栅格系统。

栅格参数
通过下表可以详细查看 Bootstrap 的栅格系统是如何在多种屏幕设备上工作的。

超小屏幕 手机 (<768px)	小屏幕 平板 (≥768px)	中等屏幕 桌面显示器 (≥992px)	大屏幕 大桌面显示器 (≥1200px)
栅格系统行为	总是水平排列	开始是堆叠在一起的，当大于这些阈值时将变为水平排列C
.container 最大宽度	None （自动）	750px	970px	1170px
类前缀	.col-xs-	.col-sm-	.col-md-	.col-lg-
列（column）数	12
最大列（column）宽	自动	~62px	~81px	~97px
槽（gutter）宽	30px （每列左右均有 15px）
可嵌套	是
偏移（Offsets）	是
列排序	是

#### 实例：手机、平板、桌面
在上面案例的基础上，通过使用针对平板设备的 .col-sm-* 类，我们来创建更加动态和强大的布局吧。

![](https://github.com/Eaaon/Bootstrap-CSS/blob/master/1.JPG)

```
<div class="row">
  <div class="col-xs-12 col-sm-6 col-md-8">.col-xs-12 .col-sm-6 .col-md-8</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>
<div class="row">
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
  <!-- Optional: clear the XS cols if their content doesn't match in height -->
  <div class="clearfix visible-xs-block"></div>
  <div class="col-xs-6 col-sm-4">.col-xs-6 .col-sm-4</div>
</div>
```
