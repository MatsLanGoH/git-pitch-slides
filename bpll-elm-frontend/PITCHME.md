## Elm でフロントエンドを楽しむ

2020-04-21

[BPLL #44](https://bpstudy.connpass.com/event/171284/)

@fab[twitter][matspod](https://twitter.com/matspod)

---

### Elm って何?

![Elm](bpll-elm-frontend/assets/elm-logo.png)

+++

### 出会ったきっかけ

@ul[brighten]

- Rust 軽く触ってみたら Elm の存在を知った。
- 2019 年に入ってから (Elm 0.19)
- 初 FP 言語。気がつけばはまっていた。

@ulend

+++

### Elm is コレ

@quote[Elm is a functional language that compiles to JavaScript. It helps you make websites and web apps. It has a strong emphasis on simplicity and quality tooling.](Elm Guide)

+++

### naruhodo

- JS にコンパイルできる関数型プログラミング言語
- 主にフロントエンドやアプリに向いている

+++

@quote[JS がんばらなくてもフロントがかけるんだ](matsu)

+++

[...ちょっと見てみよう](https://ellie-app.com/new)

+++

### Elm をどうやって覚えている?

@ul[brighten]

- [An Introduction to Elm](https://guide.elm-lang.org/): 基礎から
- Brian P. Hogan 氏 [Exercises for Programmers](https://pragprog.com/book/bhwb/exercises-for-programmers)
  - ↑ あるあるエキササイズ。新しい言語を覚える時に便利。
- [exercism.io](https://exercism.io/tracks/elm) Elm Track
  - メンターがいてくれるからいい勉強になる。

@ulend

+++

### 何か作った?

+++

@ul[brighten]

#### [天気予報アプリ](https://elm-weather-app.netlify.com/)

- [openweathermap.org](https://openweathermap.org)の API 利用
- ある意味定番的エキササイズ
- Decoder, List/map 処理, Http などのいい練習
- そろそろ修正しないと

@ulend

+++

...でもなんだか物足りない

+++

## ニコカレ的なあれ

+++

@snap[west]

![Elm Niconico](bpll-elm-frontend/assets/elm_niconico_app_1.png)

@snapend

@snap[east span-50 text-center]

@ul[brighten]

### MVP

- ログイン機能
- Mood + メッセージ登録
- 早見表

@ulend

@snapend

+++

### kwsk: 構築

@ul[brighten]

- [Django Rest Framework](https://www.django-rest-framework.org/)
- [create-elm-app](https://github.com/halfzebra/create-elm-app)
- CSS: とりあえず [tailwind.css](https://tailwindcss.com) で組み立てることに

@ulend

+++

### コード見たい方は ↓ へ

- @fab[github][client](https://github.com/MatsLanGoH/elm-niconico)
- @fab[github][api](https://github.com/MatsLanGoH/dj-niconico)
  (だいぶ放置している)

---

## 感想

+++

## Elm ちょっと困ったとこ

+++

@ul[brighten]

- JS をがちゃがちゃやるには限界がある([Ports](https://guide.elm-lang.jp/interop/ports.html))
- 関数型慣れる必要ある (for loop ほしい)
- ドキュメンテーション物足りないときある
- `Time` やたらしんどい。

@ulend

+++

## Elm のよいこと

@ul[brighten]

- [The Elm Architecture](https://guide.elm-lang.jp/architecture/) でコードが追いやすい
- 実用上ランダムエラーおきない
- null, undefined ありえない
- コンパイラが人にやさしい (学習コストがやすくなる)
- リファクタリング怖くない

@ulend

+++

@quote[I was coding the entire time and all the code worked on the first try](Richard Feldman)

@fab[youtube][building uis in the dark](https://www.youtube.com/watch?v=sKxEwjKQ5zg)

---

## おまけ: 楽しいライブラリたち

#### [Awesome Elm](https://github.com/sporto/awesome-elm)

+++

## おまけ 2: 勉強会やりたい

(以上)

+++

## リンク集

- [Elm Guide](https://guide.elm-lang.org)
- [Elm Guide 日本語版](https://guide.elm-lang.jp/)
- [Elm SPA Example](https://github.com/rtfeldman/elm-spa-example)

### THANK YOU!

plz follow:

@fab[twitter][matspod](https://twitter.com/matspod)

@fab[github][matslangoh](https://github.com/MatsLanGoH)

---
