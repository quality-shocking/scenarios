# #0 Kyon Mm

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
* 実は開発プロセスの選定は製品の品質に莫大な影響を与えうる
  * ROI高く品質をあげることがもとめられる
  * どうやって防ぐか、どうやって検知するか の両方を効率よくおこなう必要がある。
  * 誰かが楽に管理できるプロセスではなくて全体が楽になるプロセスを設計する
* 良いスクラムと悪いスクラム
* どうやったら悪いスクラムに陥ってしまっていることを自発的に気づけるのか
* テスティング手法最前線(機械学習のテスト/分散システム/bashのテスト/自動テスト/テスト駆動開発)
  * TDD界隈で、TCRという手法が考案されていま議論があついです。test && commit || revertの略になっています。https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864
* .NETの処理系の動きを自社でかなり解析しているとbleisさんが発言したことがあったと記憶しています。そのニーズはどこにあったのでしょうか？
  * とあるフレームワークの開発保守でいわゆるアスペクト指向的にログを自動ではさむフレームワークなどを開発していた。そのときにF# の式木をさわって実現していたので詳しくなった。
* テスト可能な対象物とテストでは検査できない対象物の区別
* IDEの有無は品質にどう影響するか
* 今Groovyってどんな塩梅ですか？Kotlinとかが最近は流行ってそう？
* その他今おすすめのツール

## 雑談タイム

* ソフトウェアの品質について時間いっぱいまでブレーンストーミング

## クロージング

* ホスト「と盛り上ってきたところで時間が来てしまいました。最後に一言ありますでしょうか？」
* ゲスト「XXX」
* ホスト/ゲスト「ありがとうございました!」
* ホスト「もし気に入っていただけたらチャンネル登録よろしくお願いします」

## (YouTubeページ下へ付記する)リンク集

* https://kyon-mm.com
* http://kyon-mm.hatenablog.com/
* http://www.otr-jp.com/
* 超Scrum入門〜未完成フラクタルと15minSprint〜 #RSGT2019
 https://speakerdeck.com/kyonmm/chao-scrumru-men-wei-wan-cheng-hurakutaruto15minsprint-number-rsgt2019
* xUnit Test PatternsのTest Doubleパターン(Mock、Stub、Fake、Dummy等の定義) http://goyoki.hatenablog.com/entry/20120301/1330608789

## YouTube動画

### Episode1 - Kyon Mm (take1) #qshocking

https://www.youtube.com/watch?v=AzzkQbRJmJM&t=614s

```
This is episode 1 on Quality Shocking channel. The gust is Kyon MM.

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
The 15 minutes sprint closes with "minutes report" which is very short summary for the sprint. It's useful for short communication.
Q. Why do you choose "15 minites"?
A. Just for today. We {will,may} choose shorter sprint.
Q. If ticket system broadcasts E-mail, such mail is replacement for very short splint?
A. No. Nobody can read such too many mails. We needs the summary.
https://en.wikipedia.org/wiki/Mock_object
Q. How to keep quality of semi-realtime application?
A. We cover it with specification, which derives testing and documentation.

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/0-kyonmm/
```
