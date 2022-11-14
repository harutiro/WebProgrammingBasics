第7章 CheckTest
================
k22120 牧野遥斗

## P146 CheckTest
### Q1 関数の説明で正しいものを全て選んでください。
```
B,C
```

## P154 CheckTest
### Q1 数値を渡して偶数なら「偶数」、奇数なら「奇数」と表示する関数を作成してください。
```javascript
function evenOrOdd(num){
    if(num % 2 === 0){
        return '偶数';
    }
    return '奇数';
}
```

### Q2 関数の名前で正しいものを全て選んでください
```
B,D
```


## P157 CheckTest
### Q1 名前を渡すと語尾に「さん」と液晶を足した文字列を返し、オプションで継承を指定できる関数を書いてください。
```javascript
function formatName(name, title = 'さん'){
    return name + suffix;
}
```

## P160 CheckTest
### Q1 関数式の特徴で正しいものを全て選んでください。
```
A,B,D
```

## P168 CheckTest
### Q1 以下のコードの出力結果は何になるでしょうか。
```javascript
let a = 10;
if (true){
    let a = 20;
}
console.log(a);
```

answer: 10

### Q2 グローバル変数の特徴で間違っているものを選んでください。
```
A
```