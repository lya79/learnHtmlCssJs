# css選擇器

## 各種類型的選擇器
下列資料來源參考[1].

#### 基本選擇器
1. 類型選擇器 elementname
2. Class選擇器 .classname
3. ID選擇器 #idname
4. 通用選擇器 * ns|* *|*
5. 屬性選擇器 [attr=value]
6. 狀態選擇器 a:active, a:visited
#### 複合選擇器
1. 鄰接同層選擇器 A + B
2. 通用同層選擇器 A ~ B
3. 直屬選擇器 A > B
4. 後代選擇器 A B
#### 虛擬元素
#### 虛擬類別

---

## `類型選擇器`
指定元素設定 css.
    
使用方法
```html
<span>HELLO</span>
```

CSS範例
```css
span { /* 全部的 a元素都會改變樣式 */
    background-color:red;
}
```
## `Class選擇器`
類別選擇器可套用多種類別.

使用方法
```html
<p class="red fancy">HELLO</p>
```

CSS範例
```css
/* 所有有用到 spacious類別的元素就會改變樣式 */
.spacious {
  margin: 2em;
}

/* 所有的 li元素如果有使用到 spacious類別就會改變樣式 */
li.spacious {
  margin: 2em;
}

/* 所有的 li元素如果使用的類別同時有 spacious和 elegant就會改變樣式 */
li.spacious.elegant {
  margin: 2em;

```
## `ID選擇器`

TODO

## `通用選擇器`
## `屬性選擇器`
## `狀態選擇器`
## `鄰接同層選擇器 A + B`
## `通用同層選擇器 A ~ B`
## `直屬選擇器 A > B`
## `後代選擇器 A B`
## `虛擬元素`
## `虛擬類別`

---

## 參考
1. [CSS 選擇器](https://developer.mozilla.org/zh-TW/docs/Glossary/CSS_Selector)