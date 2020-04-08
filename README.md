# dragscroll.js
兼容PC和移动端拖拽滚动jQuery插件
# 使用方法
# html:
<div class="drag-box">
  <div class="drag">这里是一段文本或者其他内容......</div>
</div>
# css:
css自定义，可以自己根据需要设置drag-box的宽高，超出隐藏等样式
# js:
<script src="../path/jquery-1.12.4.min.js"></script>
<script src="../path/jquery.dragscroll.js"></script>
<script type="text/javascript">
  $('.drag').dragscroll();
</script>
# 参数说明：
direction：null，  // 滚动方向：默认null，可选'scrollLeft','scrollTop'
onStart: function($this) {}, // 拖动开始前的回调函数
onMove: function($this) {},  // 拖动时的回调函数
onEnd: function($this) {}    // 拖动结束后的回调函数
