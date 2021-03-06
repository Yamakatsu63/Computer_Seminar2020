# Markdown基礎
Markdownとは，デジタル文章の書き方の１つ．

簡単に書くことができ，対応するツールが多いことから広く利用されている．

## 1.見出し
見出しの先頭部分に`#`をつける．

`#`が増えるごとに小さな見出しになる．

入力
```
# 大きい見出し
## 中くらいの見出し
### 小さい見出し
```

結果

---
# 大きい見出し
## 中くらいの見出し
### 小さい見出し
---

<br>

## 2.箇条書き
箇条書きには，通常の箇条書きと数字付き箇条書きの２種類がある．

- 通常の箇条書き

通常の箇条書きは，先頭部分に`-`または`*`をつけると表示できる．また，`tabキー`を使うことにより階層化ができる．

入力
```
- 通常リスト
* 通常リスト

- 階層化1
    - 階層化2-1
    - 階層化2-2
```

結果

---
- 通常リスト
- 通常リスト

- 階層化1
    - 階層化2-1
    - 階層化2-2
---

- 数字付き箇条書き
数字付き箇条書きは，先頭部分に`1.`をつけると表示できる．

入力
```
1. 数字付き箇条書き1
1. 数字付き箇条書き2
1. 数字付き箇条書き3
```

結果

---
1. 数字付き箇条書き1
1. 数字付き箇条書き2
1. 数字付き箇条書き3
---

<br>

## 3.リンク
外部サイトのリンクを表示したい場合は，`[リンク名](URL)`とすると表示できる

入力
```
[研究室Wiki](http://wiki.rel.hiroshima-u.ac.jp/)
```

結果

---
[研究室Wiki](http://wiki.rel.hiroshima-u.ac.jp/)

---

## 4.画像貼り付け

画像を貼り付けたい場合は，`![画像名](ファイルパス)`とすると画像を表示できる

入力
```
![犬](dog.jpg)
```

結果

---
![犬](dog.jpg)
---