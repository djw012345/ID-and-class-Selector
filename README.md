# ID-and-class-Selector
CSS 的 ID 和 Class 選擇器 ( 類別選擇器 )

# 一、ID 選擇器（ # ）
- 特性
```
只有 id="header" 的元素會被套用
一個頁面 只能有一個相同 ID
```

``` html
<div id="header">
    這是標題區
</div>

<!-- CSS 程式碼 -->
<style>
#header {
    background-color: blue;
    color: white;
    height: 100px;
}
</style>
```

# 二、Class 選擇器（ . ）
```html
<p class="text">
    第一段
</p>

<p class="text">
    第二段
</p>

<style> 
.text {
    color: red;
    font-size: 20px;
}
</style>
```




