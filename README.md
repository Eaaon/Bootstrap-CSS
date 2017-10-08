# Bootstrap-CSS
[Bootstrap全局CSS样式学习](http://v3.bootcss.com/css/#overview)

设置全局 CSS 样式；基本的 HTML 元素均可以通过 class 设置样式并得到增强效果；还有先进的栅格系统。

实例：手机、平板、桌面
在上面案例的基础上，通过使用针对平板设备的 .col-sm-* 类，我们来创建更加动态和强大的布局吧。

.col-xs-12 .col-sm-6 .col-md-8.col-xs-6 .col-md-4
.col-xs-6 .col-sm-4.col-xs-6 .col-sm-4.col-xs-6 .col-sm-4
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
