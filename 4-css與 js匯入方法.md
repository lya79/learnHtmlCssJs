# CSS與 JS匯入方式
CSS與 JS都有三種匯入方法(行內匯入、網頁內匯入、外部匯入).

---

## CSS
### 行內匯入
在 body內的任何 html標籤使用 css.
```html
<h1 style="color:red"></h1>
```
### 網頁內匯入
head內使用 style標籤, 並且在標籤內寫 css
```html
<head>
  <style type="text/css">
    div {
      background-color:#FF0000;
    }
  </style>
</head>
```
### 外部匯入
head內使用 link標籤, 搭配 href屬性指定 css檔案 
```html
<head>
<link rel=stylesheet type="text/css" href="my.css">
</head>
```
---

## JS
### 行內匯入
在 body內的任何 html標籤使用 js.
```html
<div ... onclick="..."...></div>
```
```html
<body>
  <script>
    document.write("<h1>这是一个标题</h1>");
    document.write("<p>这是一个段落。</p>");
  </script>	
</body>
```
### 網頁內匯入
head內使用 script標籤, 並且在標籤內寫 js
```html
<head>
  <script>
    function myFunction(){
      document.getElementById("demo").innerHTML="hello";
    }
  </script>
</head>
<body>
  <p id="demo">一个段落。</p>
  <button type="button" onclick="myFunction()">click</button>	
</body>
```
### 外部匯入
head內使用 script標籤, 搭配 src屬性指定 js檔案. 也可以把 srcipt放在 body區塊內也有一樣的作用.
```html
<head>
  <script src="my.js"></script>
</head>
<body>
  <button type="button" onclick="myFunction()">点击这里</button>
</body>
```

---

## 參考
1. [CSS 套用方式](https://www.1keydata.com/css-tutorial/tw/apply.php)
2. [JavaScript 用法](http://www.runoob.com/js/js-howto.html)

---

## 心得
上述幾種方法只是基礎的方法. 大致上先了解即可.