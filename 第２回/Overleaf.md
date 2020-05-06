# Overleaf入門

[Overleaf](https://ja.overleaf.com/)はWeb上で利用できるオンラインTeXエディタである．

## 日本語入力の設定

1. 左上の「メニュー」をクリックし，コンパイラを`pdfLatex`から`Latex`に変更する．
1. latexmkrcというファイルを作る．

```
$latex = 'platex';
$bibtex = 'pbibtex';
$dvipdf = 'dvipdfmx %O -o %D %S';
$makeindex = 'mendex -U %O -o %D %S';
$pdf_mode = 3; 
```

## コンパイル

Overleafでコンパイルする方法は２つある．
- `Ctrl + Enter`または「再編集」ボタンを押す
- 「再編集」ボタンのプルダウンメニューでAuto Compileをオンにする

## PDF出力
画面右のOverViewタグの左上にある`PDFをダウンロード`をクリックする．