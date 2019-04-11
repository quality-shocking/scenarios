# Episode1 - Kyon Mm (take1)

(書き方の例として[テンプレート](../../template/README.md)を参照してください)

## 収録場所/日時

* 時間: 2019-03-31 12:00-15:00
* 会議室: [東京都千代田区神田須田町2-3-1 NBF神田須田町ビル7F](https://goo.gl/maps/8R75fjgvfrG2) [永和システムマネジメントコワーキングスペース](https://www.esm.co.jp/coworking/)
* 集合時間/場所: 2019-03-31 11:45 [同ビル1階のファミリーマート](https://goo.gl/maps/cGdWDkz1h372)
* 緊急連絡先: 090-3524-7064

## 番組の紹介

* ホスト/ゲスト「こんにちはー」
* ホスト「クオリティショッキングは毎回ゲストを迎えてソフトウェアの品質についてあーでもないこーでもないと話しあうチャンネルです。」

## ゲストの紹介

* ホスト「Kyonさんこんにちは。まずは簡単に自己紹介をしていただけますか？」
* ゲスト「こんにちは皆さん。きょんです。Twitterではkyon_mmでやっています。kyon-mm.com で個人事業主もやっています。アジャイルコーチ、テストアーキテクト、研修など仕事しています。」

## 具体的な議論

* 現在、株式会社オンザロードで運用されているスクラム/テストなど品質への取り組み
  * フラクタルなスプリント
  * Minutesレポート
  * インテグレーションテストを重視したTDD
  * 柔軟なテストダブルWebAPIアプリケーション
  * 性能テスト
  * デイリーであらためてコードレビュー
  * いわゆる非機能要件によって設計を決定する
* 15分スプリントって、短かすぎないですか、、、やはり2週間が妥当なのでは。。。
* .NETの処理系の動きを自社でかなり解析しているとbleisさんが発言したことがあったと記憶しています。そのニーズはどこにあったのでしょうか？
  * とあるフレームワークの開発保守でいわゆるアスペクト指向的にログを自動ではさむフレームワークなどを開発していた。そのときにF# の式木をさわって実現していたので詳しくなった。

## (YouTubeページ下へ付記する)リンク集

* https://kyon-mm.com
* http://kyon-mm.hatenablog.com/
* http://www.otr-jp.com/
* 超Scrum入門〜未完成フラクタルと15minSprint〜 #RSGT2019
 https://speakerdeck.com/kyonmm/chao-scrumru-men-wei-wan-cheng-hurakutaruto15minsprint-number-rsgt2019
* xUnit Test PatternsのTest Doubleパターン(Mock、Stub、Fake、Dummy等の定義) http://goyoki.hatenablog.com/entry/20120301/1330608789
* Spockのレポート生成はHTML, Markdown, Asciidocできるし、カスタムも出来るんだぜ http://kyon-mm.hatenablog.com/entry/2017/12/16/100000

## YouTube動画

https://www.youtube.com/watch?v=AzzkQbRJmJM&t=614s

```
This is episode 1 on Quality Shocking channel. The guest is Kyon MM.

https://kyon-mm.com/
http://kyon-mm.hatenablog.com/
株式会社オンザロード http://www.otr-jp.com/

Q. Why do you choose .NET?
A. A customer chose it.
Integration and system testing is more important than unit testing on TDD.
Firstly write test for web API, secondly implement the API.
It means interface first style.
We should create prototype to get the interface.
Right product stands on third implementation.
Kyon's team needs only ONE DAY for the third implementation!
Kyon's team sprint is built on fractal. The minimum is 15 minutes!
A way to the 15 minute sprint. https://speakerdeck.com/kyonmm/chao-scrumru-men-wei-wan-cheng-hurakutaruto15minsprint-number-rsgt2019
The 15 minutes sprint closes with "minutes report" which is very short summary for the sprint. It's useful for short communication.
Q. Why do you choose "15 minites"?
A. Just for today. We {will,may} choose shorter sprint.
Q. If ticket system broadcasts E-mail, such mail is replacement for very short splint?
A. No. Nobody can read such too many mails. We need the summary.
https://en.wikipedia.org/wiki/Mock_object
http://goyoki.hatenablog.com/entry/20120301/1330608789
Q. How to keep quality of semi-realtime application?
A. We cover it with specification, which derives testing and documentation.
http://kyon-mm.hatenablog.com/entry/2017/12/16/100000

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/1-kyonmm-take1/
```
