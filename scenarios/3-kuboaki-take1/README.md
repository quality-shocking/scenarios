# #1 Shin Kuboaki

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

* ホスト「Kuboakiさんこんにちは。まずは簡単に自己紹介をしていただけますか？」
* ゲスト「こんにちは皆さん。くぼあきです。astah* というUMLやSysMLを扱うモデリングツールを販売しているチェンジビジョンという会社で働いています。私の仕事は、主に、モデルを使う人を作ること、プリセールスですね。他に、技術研修の教材開発、講師、大学非常勤講師、ETロボコンというロボコンの本部審査員などもやっています。周囲からは、ひどい雨男と呼ばれることが多く、日本雨女雨男協会会員（IT本部長）なんて肩書ももっています。今日は、仕事の話もしますが、話は基本的に私個人の考えとおもってください。

## 具体的な議論

* UMLモデリングツールの不具合の低減策や再発防止手法
  - ツールの場合、ツール自体の不具合の問題と、ツールで作成するモデル図の課題、不具合というのがあります。
  - モデリングツールの不具合の多くは、操作や表示、モデルリポジトリのデータに含まれます。これらのうち、表示データとリポジトリのデータは、ツールの変更前後（あるいは期待値と結果）のデータを比較すれば、調べられます。操作の不具合は、そう簡単でもないですね。再現性を確保するのも難しいことがあります。
* というかそもそも図の再現性をテストすることって、、、どうやるんですか。。。
  - 同じ操作をして、結果の表示とリポジトリのなかで関心がある部分が変化していないかを調べます。前者は、画像に置き換えて、画像の差分をチェックします。ただし、見かけの差異しかわからないので、リポジトリのデータも比較します。
* 「モデル駆動開発」という単語を最近聞かなくなったのですが、皆MATLAB/Simulinkに吸いこまれたのでしょうか。。。
  - モデル駆動は今でも多くの開発現場で使われています。たとえば、コード変換とか、コード生成などといわれているものは、モデルからモデルへ一定のルールで変換するものなので、実はモデル駆動が提唱する方法の具体的な実施形態とみなすことができます。入力がUMLやSysMLということですと、自動車業界などが？MBSEで対応しようとしている「AUTOSAR (オートザー）」では、設計したモデルを、ターゲットプラットフォームのモデルと結合して、そこからコードを生成する方法を想定した開発手法の標準化を目指しています。自動車のECUをモデル駆動で開発するという考え方とみてもよいでしょう。

## (YouTubeページ下へ付記する)リンク集

* https://www.facebook.com/kuboaki
* http://www.change-vision.com/

## YouTube動画

xxx リンク

```
This is episode 3 on Quality Shocking channel. The guest is Shin Kuboaki.

https://www.facebook.com/kuboaki
株式会社チェンジビジョン http://www.change-vision.com/

Astah UML http://astah.net/editions/uml-new
Unified Modeling Language (UML) https://en.wikipedia.org/wiki/Unified_Modeling_Language
Systems Modeling Language (SysML) https://en.wikipedia.org/wiki/Systems_Modeling_Language
Selenium automates browsers https://www.seleniumhq.org/
Model-driven architecture (MDA) https://en.wikipedia.org/wiki/Model-driven_architecture
Ruby on Rails https://rubyonrails.org/
Scaffold in Rails https://guides.rubyonrails.org/command_line.html
MATLAB https://www.mathworks.com/products/matlab.html
Simulink https://www.mathworks.com/products/simulink.html

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/3-kuboaki-take1/
```
