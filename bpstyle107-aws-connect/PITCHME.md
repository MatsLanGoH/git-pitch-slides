
## Amazon Connect を完全に理解した話

2019-10-03

[BP-Style 107]

@fab[twitter][matspod](https://twitter.com/matspod)

---

## CONTENTS

@ul[brighten]

* Amazon Connect is 何?
* Connect: できること
* Connect: できないこと
* これどうかな...編
* インターフェースデザインの話
* ユーズケース紹介

@ulend

---

### Amazon Connect is 何?

@ul[brighten]

* AWS サービス
* コールセンターの作成ツール
* ボタン入力
* 音声認識 (Polly, Lex)

@ulend

---

### Connect: できること

@ul[brighten]

* 音声、ボタン入力で会話フローを形成する
* DynamoDB, S3 などAWSサービスと連携し情報取り出す
* Lambdaで外部サービス連携

@ulend

---

### Connect: できないこと

@ul[brighten]

* ニホンゴ（※）
* そもそも英語以外はよわよわ
* フリーダイヤル（※）

@ulend

---

### これどうかな...編

@ul[brighten]

* フローエディタはベータ版（な感じ）
* プロジェクト間の情報移行がしづらい
* 日本語分割...

@ulend

+++

### 日本語の分割、難しい


```html
<speak>
こんにちは。機器故障のご連絡は
<break time="0.1s\"/>１<break time=\"0.2s\"/> を入力してください。
</speak>
```

@[3]

+++

---

### インターフェースデザインの話

@ul[brighten]

* 画面を音声出力するだけじゃダメ
* 長文、曖昧な文はダメ
* ユーザーに再確認のチャンスを与えないとダメ

@ulend

+++

### UI/UX ガイドライン

* [Alexa VUI](https://developer.amazon.com/ja-JP/alexa/alexa-skills-kit/vui)
* [Google Conversation Design](https://designguidelines.withgoogle.com/conversation/conversation-design/what-is-conversation-design.html#what-is-conversation-design-what-isnt-conversation-design)

---


### ユーズケース紹介

@ul[brighten]

* ありそうなケース
* 面白そうなケース

@ulend

+++

### ありそうなケース

@ul[brighten]

* 予約システム（レストランなど
* 在庫確認システム
* 対応状況確認システム

@ulend

+++

### 面白そうなケース

@ul[brighten]

* 多言語ガイド
* バリアフリー案内
* 障害モニタリング

@ulend

---

### THANK YOU!

plz follow:

@fab[twitter] [matspod](https://twitter.com/matspod)

---
