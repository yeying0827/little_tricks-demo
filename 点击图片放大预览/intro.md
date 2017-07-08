## 点击图片放大预览（jquery+zoomify）

- 和其他使用jQuery插件的使用方法类似，先引入jQuery，再引入插件。
```html
<script src="./js/jquery-1.10.2.min.js"></script>
<script src="./js/zoomify/js/zoomify.min.js"></script>
```
- 引入插件相关的样式文件
```html
<link rel="stylesheet" href="./js/zoomify/css/bootstrap-grid.min.css" />
<link rel="stylesheet" href="./js/zoomify/css/zoomify.min.css" />
```
- 然后就可以使用了
```html
<body>
   <img src="./images/c.c..jpg" alt="" class="zoomify-img">

   <script type="text/javascript">
       $('.zoomify-img').zoomify();
   </script>
</body>
```