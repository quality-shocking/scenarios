# Episode2 - Kyon Mm (take2)

(書き方の例として[テンプレート](../../template/README.md)を参照してください)

## 収録場所/日時

* 時間: 2019-03-31 12:00-15:00
* 会議室: [東京都千代田区神田須田町2-3-1 NBF神田須田町ビル7F](https://goo.gl/maps/8R75fjgvfrG2) [永和システムマネジメントコワーキングスペース](https://www.esm.co.jp/coworking/)
* 集合時間/場所: 2019-03-31 11:45 [同ビル1階のファミリーマート](https://goo.gl/maps/cGdWDkz1h372)
* 緊急連絡先: 090-3524-7064

## 番組の紹介

* ホスト/ゲスト「こんにちはー」
* ホスト「クオリティショッキングは毎回ゲストを迎えてソフトウェアの品質についてあーでもないこーでもないと話しあうチャンネルです。」

## 具体的な議論

* いわゆる非機能要件によって設計を決定する
* 実は開発プロセスの選定は製品の品質に莫大な影響を与えうる
  * ROI高く品質をあげることがもとめられる
  * どうやって防ぐか、どうやって検知するか の両方を効率よくおこなう必要がある。
  * 誰かが楽に管理できるプロセスではなくて全体が楽になるプロセスを設計する
* 良いスクラムと悪いスクラム
* どうやったら悪いスクラムに陥ってしまっていることを自発的に気づけるのか
* テスティング手法最前線(機械学習のテスト/分散システム/bashのテスト/自動テスト/テスト駆動開発)
  * TDD界隈で、TCRという手法が考案されていま議論があついです。test && commit || revertの略になっています。https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864
* テスト可能な対象物とテストでは検査できない対象物の区別
* IDEの有無は品質にどう影響するか
* 今Groovyってどんな塩梅ですか？

## クロージング

* ホスト「と盛り上ってきたところで時間が来てしまいました。最後に一言ありますでしょうか？」
* ゲスト「XXX」
* ホスト/ゲスト「ありがとうございました!」
* ホスト「もし気に入っていただけたらチャンネル登録よろしくお願いします」

## (YouTubeページ下へ付記する)リンク集

* https://kyon-mm.com
* http://kyon-mm.hatenablog.com/
* http://www.otr-jp.com/

## YouTube動画

https://www.youtube.com/watch?v=lkB4K1zKaUs

```
This is episode 1 on Quality Shocking channel. The guest is Kyon MM.

https://kyon-mm.com/
http://kyon-mm.hatenablog.com/
株式会社オンザロード http://www.otr-jp.com/

Customer also joins the agile process.

Architecture should be based on non-functional requirements.
Because functional requirement often change, but non-functional requirement often NOT change!

We should keep return on investment(ROI) is high.
It means our process keeping both high ROI and high development performance.
Please imagine if you take relapse prevention, you may intoroduce some tools such like lint to get high ROI and high quality.

Q. How to find my scrum is wrong?
A. It's found by saying "we are enjoying on our process" by all team members. If anyone feeling bad on the process, the process is wrong.

test && commit || revert (TCR)
https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864
Q. I think many of committers choose TCR method manually.
A. Automated TCR enforces patches to be atomic and small.

Q. I'm using Emacs. But today is the day to switch to the other rich IDE?
A. Case by case. We should be able to use the other environment at team.

Groovy 3.0 will be compatible with Java 8.
And Groovy will introduce gradual typing!

Q. Total application based on Linux/Groovy may have some bug. How to take the relapse prevention?
A. It needs much evaluation for the Groovy tech.

At future, we should get process without any testing!!!

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/2-kyonmm-take2/
```
