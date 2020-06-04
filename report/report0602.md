## 学んだこと

## HTML 特殊文字


- &amp;(&)
- &copy;(©)
- &nbsp;( )
  > http://www.shurey.com/js/labo/character.html

## mixin

例）

```
// スタイル定義
btn(font-color = #000)
  color font-color
  font-size 14px
  font-weight bold

// スタイル呼び出し
.btn-A
  btn()
  width 200px
.btn-B
  btn(#f0f)
  width 150px
.btn-C
  btn #ff0
  width 100px
```

### メタ言語

CSS メタ言語は、CSS の生産性向上の為に拡張された技術です。

## stylus

- できること
  - 変数
  - 継承
  - mixin など

## json とは

テキストベースのデータフォーマット

### json 形式

{}でくくりその中にデータを書く
"name":"田中"

```
[
 {"id": 1, "name":"商品A", "price":1280},
 {"id": 2, "name":"商品B", "price":480},
 {"id": 3, "name":"商品C", "price":980}
]
```

ダブルクォーテーションを忘れないことが大事

## php PSR2

コーディングのガイド <br>
品質をためにガイドにそうこと

## 変数名

- 変数名はわかりやすくかく

## 型名の確認

大枠の意味を理解する

## 三項演算子

## スーパーグローバル変数

- \$GLOBALS
- \$\_SERVER
- \$\_GET
- \$\_POST
- \$\_FILES
- \$\_COOKIE
- \$\_SESSION
- \$\_REQUEST
- \$\_ENV
