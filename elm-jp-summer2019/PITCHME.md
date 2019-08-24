
## ElmとDRFでニコカレを作ってみた話

2019-08-25 Elm in Japan Summer 2019

@fab[twitter] [@matspod](https://twitter.com/matspod)

---

## CONTENTS

@ul[brighten]

* お前誰よ
* Elmの覚え方
* いま何を作っている？

@ulend

---

### お前誰よ

@ul[brighten]

* Matthias Lambrecht（matsu）
* ドイツ生まれ(日本在住11年くらい)
* 3児の父（5y/2y/0y）
* キーボード作りが趣味 （最近凍結気味）

@ulend

+++

### 普段は何やっているの？

@ul[brighten]

* [BeProud](https://www.beproud.jp)でフルスタックエンジニア
  * 日頃Python書いている (Django案件が多い)
  * Pythonメインで受託開発など
  * [Connpass](https://connpass.com), [PyQ](https://pyq.jp)
* [(We're hiring)](https://www.beproud.jp/careers/)

@ulend

---

@ul[brighten]

### Elmの覚え方

@ul[brighten]

* Rust軽く触ってみたらElmの存在を知った。
* 2019年に入ってから (0.19)
* 初FP言語。気がつけばはまっていた。

@ulend
+++

### Elmをどうやって覚えている?

@ul[brighten]

* 公式ガイドの課題説いてみたり
* Brian P. Hogan氏 [Exercises for Programmers](https://pragprog.com/book/bhwb/exercises-for-programmers)
  * ↑あるあるエキササイズ。新しい言語を覚える時に便利。
* [exercism.io](https://exercism.io/tracks/elm) Elm Track
  * メンターがいてくれるからいい勉強になる。

@ulend

+++

### 何か作った?

@ul[brighten]

* [天気予報アプリ](https://elm-weather-app.netlify.com/)
* [openweathermap.org](https://openweathermap.org)のAPI利用
* ある意味定番的エキササイズ
* Decoder, List/map処理, Httpなどのいい練習

@ulend

+++

...でもなんだか物足りない

---

## いま何を作っている?

+++

## 以下を求む

@ul[brighten]

* 日常的に使いたいもの → モチベーション
* APIも含めて何かを作る → 技術的挑戦
* optional: 仕事で役にたつ何か。

@ulend

+++

## よし、ニコカレを作ろう！

+++

@snap[west span-40 text-center]

### Elm niconico

![Elm Niconico](elm-jp-summer2019/assets/elm_niconico_app_1.png)

@snapend

@snap[east span-40 text-center]

@ul[brighten]

* ログイン機能
* Mood + メッセージを登録できる
* 過去１ヶ月分の気分確認できる

@ulend

@snapend
+++

### 作り方は簡単

@ul[brighten]

* APIを用意する
* Clientをチャチャっと作りあげる
* デプロイする
* うぇ〜い

@ulend

+++

### kwsk: API

@ul[brighten]

* [Django Rest Framework](https://www.django-rest-framework.org/)
* Djangoベースで簡単にRESTful APIが作れる。

@ulend

+++

### 簡単じゃなかった

+++

### ところで、DRF is 何？


---

## 開発してみてわかったこと

@ul[brighten]

* [Insomnia REST Client](https://insomnia.rest)がめちゃ便利。
*
*

@ulend

---

---

### 反省点

@ul[brighten]

*
*
*

@ulend

---

@ul[brighten]

*
*
*

@ulend

---

