# # css選擇器

HTML套用 css的方法基礎分為三種(元素、類別、id).

## 元素
```html
<head>
  <style>
    img { <!-- 只要是使用 img元素都會受影響 -->
        border-radius: 10px;
    }
  </style>
</head>
<body>
<img src="1.jpg">
<img src="2.jpg">
</body>
```
## 類別(class)
```html
<head>
  <style>
    .place { <!-- 只要是套用此類別的元素都會受影響 -->
        background: red;
    }
  </style>
</head>
<body>
<div class="place">
</div>
<div class="place">
</div>
</body>
```

## id
```html
<head>
  <style>
    #content { 
        background: red;
    }
  </style>
</head>
<body>
<div id="content">
</div>
</body>
```

## 參考
1. [CSS 選擇器
](https://developer.mozilla.org/zh-TW/docs/Glossary/CSS_Selector)
2. [CSS 选择器参考手册](https://www.w3school.com.cn/cssref/css_selectors.asp)
3. [CSS选择器笔记](http://www.ruanyifeng.com/blog/2009/03/css_selectors.html)
4. [CSS 選擇器、選擇器的優先順序和權重
](https://codertw.com/%E5%89%8D%E7%AB%AF%E9%96%8B%E7%99%BC/179545/)

## 心得
基礎的選擇器就如同上面列出的三種, 實際上還有許多種. 在實際運用時還需要考慮到情境, 選擇使用適當的選擇器. 因此還需要花時間去了解其他種類的選擇器.