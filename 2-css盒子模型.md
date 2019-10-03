# CSS
css(Cascading Style Sheets)

## 盒子模型(box model)
- margin
  - border
    - padding
      - content 

### 說明
- content: 為內容像是文字或圖片, 可以設定寬度和高度
- padding: 包圍整個 content, 透明的, 用於控制邊界(border)與內容的距離
- border: 包圍整個 padding, 不透明, 可設定粗細與顏色,
- margin: 包圍整個 border, 透明的, 用來設定邊界(border)與其他元素的距離

### margin與 padding使用
margin、padding分別有上右下左可以以設定. 表達方法有下列四種.

使用一個數字表示
```html
<div padding:20px> <!-- 上下左右都定 20px-->
</div>
```

使用二個數字表示
```html
<div padding:20px 60px> <!-- 上下設定 20px, 左右設定 60px -->
</div>
```

使用三個數字表示
```html
<div padding:20px 60px 100px> <!-- 上 20px, 左右 60px, 下 100px -->
</div>
```

使用四個數字表示
```html
<div padding:20px 60px 100px 140px> <!-- 上 20px, 右 60px, 下 100px, 左邊 140px -->
</div>
```

## 參考
1. [The CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)

## 心得
每個元素都能藉由盒子模型去修改距離相關的設定, 但是需要注意`行內元素`時, 可能會導致部份設定無效.