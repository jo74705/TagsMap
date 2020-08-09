### CSS 基本介紹

在網頁設計中，我們用 CSS 改變元素樣式

#### CSS使用方法

**CSS Selector (CSS選擇器)**

當我們在 HTML 中定義元素後我們需要去找出我們要改變的元素

例如我要改變下方`<div>`的背景顏色
```
<div class="box">
    
</div>
```

那就要用

```
.box {
    background-color: "pink"
}
```

翻成白話來說，就是我要修改某個`div` 的 class (attribute) 值為 "box" ，將其背景顏色改為粉紅色。

在 `.box{ }` 的大括號中放置CSS語法就是最基本的CSS使用方式。

常用的 selector 方法：
#### class
算是最常用的，在 HTML 中允許多個元素擁有相同的 class 名稱，也就是說當我們需要多個元素擁有共同的style的時候，就非常方便。
```
.box{

}
<div  class="box"> </div>
<div  class="box"> </div>
<div  class="box"> </div>
<div  class="box"> </div>
```
#### id
在 HTML 中 id 是為一值，不建議使用。
```
#boxId1 {

}
#boxId2 {
 
}
<div  class="boxId1"> </div>
<div  class="boxId2"> </div>
```
#### 元素名稱 (a, li, div)

針對本頁所有元素改變 style

```
li div {
  text-decoration: none;
}
a {
  text-decoration: none;
}
```

