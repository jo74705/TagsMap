### HTML 基本介紹

最基本的 HTML格式
```
<!DOCTYPE html><html<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>

  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

存成.html檔後用瀏覽器打開的結果就會是下面這樣HTML 

#### Tag 通常 都是成雙成對的
由兩個角括號圍繞起來的就成為Tag(標籤)
例如常見的:
```
<div> </div>
<a> </a>
<span> </span>
```

而如果我們在Tag中放如其他元素（純文字或是其他Tag）
例如:
```
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
```
我們就會稱 `<h1/>` 和 `<p/>` 是 `<body/>` 的子元素 (child element)
反過來說對於 `<h1>`，`<body>` 就是 `<h1>`的父元素(parent element)
~~不要問我為什麼不叫母元素~~ https://www.zhihu.com/question/21111030
常見的HTML Tag
`<div>` `<a>` `<head>`
都有不同的功能

可以從W3C的網站檢視相對應的功能：<https://www.w3schools.com/html/html_elements.asp>

完整Tag 列表：<https://www.w3schools.com/tags/default.asp>

# HTML attribute
### Attribute（特性) 
~~不是attitude (態度）~~

attribute特性由HTML定義，所有出現在HTML標籤內的描述節點都是attribute特性。
<div id="test" class="button" custom-attr="1"></div>

attribute的型態總會是**字串**
以上面的DIV為例 *id* *class* *custom-attr* 都是 attribute

