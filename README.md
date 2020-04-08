# dragscroll.js
兼容PC和移动端拖拽滚动jQuery插件
## 使用方法
### html:
<div class="drag-box">
  <div class="drag">这里是一段文本或者其他内容......</div>
</div>
### css:
css自定义，可以自己根据需要设置drag-box的宽高，超出隐藏等样式
### js:
1. <script src="../path/jquery-1.12.4.min.js"></script>
2. <script src="../path/jquery.dragscroll.js"></script>
3. <script type="text/javascript">
4.   $('.drag').dragscroll();
5. </script>
### 参数说明：
1. direction：null，  // 滚动方向：默认null，可选'scrollLeft','scrollTop'
2. onStart: function($this) {}, // 拖动开始前的回调函数
3. onMove: function($this) {},  // 拖动时的回调函数
4. onEnd: function($this) {}    // 拖动结束后的回调函数
