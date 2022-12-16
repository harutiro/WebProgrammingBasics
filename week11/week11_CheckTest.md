第13章 CheckTest
================
k22120 牧野遥斗

## P257 CheckTest
### Q1 DOMの機能が使えるのは、何という名前のオブジェクトですか？
document / window.document

### Q2 DOMの役割を一言でいうと何というでしょうか？
JavascriptでHTMLを操作するための仕組み

### Q3 DOMはOO構造という入れ子になっています。何構造でしょうか？
ツリー構造

## P262 CheckTest
### Q1 上記のHTMLからid属性がtestの要素を取得するコードをかいてください。
```javascript
const test = document.querySelector("#test");
```

### Q2 上記のHTMLからclass属性がtestの要素を取得するコードをかいてください。
```javascript
const test = document.querySelector(".test");
```


### Q3 上記のHTMLからclass属性がitemの要素をすべて取得するコードをかいてください。
```javascript
const test = document.querySelectorAll(".item");
```

<div class="page"/>


## P268 CheckTest
### Q1 要素のテキストを変更するのは何という名前のプロパティでしょうか？
textContent

### Q2 <a>要素のリンク先をhttps://example.com/surasuraに変更するコードを書いてください。

```html
<a href="https://example.com/surasura">スラスラ</a>
```

```javascript
const link = document.querySelector("a");
link.href = "https://example.com/surasura";
```

## P274 CheckTest
### Q1 文字と文字の隙間幅を指定するCSSのletter-spacingプロパティをJavascriptで10pxに変更するコードを書いてください。
```html
<style>
p{letter-spacing: 10px;}
</style>
<p>このテキストの文字幅を変更してください。</p>
```

```javascript
const element = document.querySelector("p");
element.style.letterSpacing = "10px";
```


### Q2 以下の要素のClass属性をJavaからJavascriptに変更するコードを書いてください。
```html
<div class="Java">Java</div>
```

```javascript
const element = document.querySelector(".Java");
element.classList.replace("Java", "Javascript");
```

<div class="page"/>


## P284 CheckTest
### Q1 以下の要素を作成するコードを書いてください。
```html
<div>新しく作る要素</div>
```

```javascript
const element = document.createElement("div");
element.textContent = "新しく作る要素";
```

### Q2 以下のコメント部分に要素を追加するために、[?]に記述するべきコードとして正しいものを全て選んでください。
```html
<div class="test">
    <!-- ここに追加したい -->
    <div class="child"></div>
</div>
<script>
    const newElement = document.createElement("div");
    [?]
</script>
```

```javascript
A , C
```


