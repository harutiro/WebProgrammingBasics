第6章 CheckTest
================
k22120 牧野遥斗

## P112 CheckTest
### Q1 以下のコードを実行した時に出力されるのはAとBどちらですか？
```javascript
const year = 2001;
if(year < 2021){
    console.log('A');
}else{
    console.log('B');
}
```

```
B
```

### Q2 以下の条件を満たすコードを書いてください。

- もし変数ageが18なら「新成人」と出力
- もし変数ageは18より上なら「成人」と出力
- 上記以外なら「未成年」と出力

```javascript
if(age == 18){
    console.log('新成人');
} else if(age > 18){
    console.log('成人');
} else {
    console.log('未成年');
}
```

## P116 CheckTest
### Q1 以下の条件を満たす条件式を選んでください
```
A
```

## P118 CheckTest
### Q1 以下のif分を三項演算子をつかって書き換えてください。
```javascript
const a = 5;
const b = 3;
const c = (a <= b)? a : b;
```

## P122 CheckTest
### Q1 Switch文がif分と比較してメリットになる説明で正しいものを選んでください。
```
B
```