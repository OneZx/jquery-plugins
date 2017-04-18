> 引用jquery和column插件

```js
<script src="jquery.js"></script>
<script src="jquery.columns.js"></script>
```

> 包含一个预先构建的列或创建自己的主题

```html
<link rel="stylesheet" href="css/classic.css">
```
> 定义一个空的div

```html
<div id="columns"></div>
```

> 初始化columns

```js
<script>
  $(document).ready(function() {
    var json = [{"col1":"row1", "col2":"row1", "col3":"row1"}, {"col1":"row2", "col2":"row2", "col3":"row2"}]; 
    $('#columns').columns({data:json});
  });
</script>
```