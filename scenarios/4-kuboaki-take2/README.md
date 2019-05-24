# Episode4 - Shin Kuboaki (take2)

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

* オブジェクト指向であるべき時と関数的であるべき時
  - UMLを使ったモデルは、離散的なイベントに対して副作用を期待する動作を示すのに向いています。これはオブジェクト指向と相性がよいです。
  - モデルベース（MATLAB/Simulinkを使った)開発では、実質的に、運動方程式のような微分方程式や伝達関数を求め、シミュレーションして係数の最適化をし、これをC言語の関数に変換しています。たとえば、フィードバック制御の操作量を求めるC言語の関数を作っていて、モデルはその中の計算のために作るというわけです。このような場合には、関数的な考え方の方が対応づけがやりやすいでしょう。
* Rubyという(見た目には)シンプルな言語の上になぜRailsという巨大な怪物が産まれてしまったのか
  - Railsが巨人かどうかは、JavaにおけるJ2EEがそうであるのと同様に、言語と、その上に実用のために積み上げたライブラリセット（＝フレームワーク）との違いでしょう。Railsが巨人なのは、データベース駆動と呼ばれる形式のWebアプリケーションが、複数の技術の集積物で、それぞれに対して対応するプログラミングモデルとそのモデルに基づくライブラリを用意したからですね。たとえば、Active Modeｌ、Active Record、Action Mailerなどがそれです。つまり、他の同様のフレームワークも同じように巨人であると言えるでしょう。
* Railsのバージョン互換性
  - Railsは、新しいことを試すことを前提に開発を進めています。それは、Webアプリケーションにおいては、使われる技術や新しいWebメディアを実現するためのアイディアが常に変化しています。私の考えですが、Railsの開発者たちが、古い考え方で構成したアプリケーションを作る方法を堅持するより、変化に追従することを選んでいるからだと思います。
* Railsで素早くプロトタイプ設計して、枯れたAPIを少しずつJavaのような硬い言語で置換することは可能なのか
  - データモデルに蓄積するデータを集める機構としてのアプリケーションということなら、可能でしょう。RubyやRailsというより、モダンなUIに対応するアプリケーションがかいはつできるフレームワークがあるかどうかだと思いますね。それがあるJavaフレームワークがあれば、対応付けて置き換えていけるようになるでしょう。そうでないなら、むずかしいはずです。
* 車載開発ならでは品質担保の現状と課題
  - 組込み開発として、
* 車載では要求は厳密に管理しているのに、仕様は厳密に管理していないと聞いたのですが本当ですか？
  - それは私にはわかりません。差分開発が多く、コードの修正が中心ということはあります。ただ、いまは自動車の電気/電子に関する機能安全についての国際規格であるISO 26262などがあるので、きちんと各工程のエビデンスを残すことが必要になってきていると思います。
* LEGO Mindstormsは初版リリースでなぜあれほどの品質を達成することができたのか
  - それはあの製品のどの側面を指していますか？
* 実は製品の品質にはお国柄が影響しているのではないか(日本/米国/中国/イギリス/フランス/ドイツ/ロシア/フィンランド/スウェーデン/デンマーク/オーストラリア)
  - 私はそうは思わないです。どんな作り方をするの次第だとおもいますね。
* ソフトウェアはそれを設計する人々の社会構造を写し込む鏡
* ソフトウェア教育において、ただ作ってデバッグするだけではなく品質が必要なのだということを何時どのように教えるべきか
  - コードを書くときに考えながら作る部分を減らすことですね、。
* コンサルタントして営業活動をするコツ
  - 人が困っているなら、答えを用意していなくても話を聞くということでしょう。
* 楽しさと成果物の品質との相関
  - 自分のこだわりが活かせるかどうか、失敗したときに前に戻れるかどうか。といったところでしょう。
* 人生において博士を取るということの価値
  - 私は勤めて10年目に、前期課程において修士をとっただけですが、仲間には取得した人がたくさんいます。いまは、理解を示す企業も増え、社会人向け大学院も増えて、通いやすくなってきていますよね。多くの方は、大学教員、あるいは企業研究員として働いています。

## クロージング

* ホスト「と盛り上ってきたところで時間が来てしまいました。最後に一言ありますでしょうか？」
* ゲスト「XXX」
* ホスト/ゲスト「ありがとうございました!」
* ホスト「もし気に入っていただけたらチャンネル登録よろしくお願いします」

## (YouTubeページ下へ付記する)リンク集

* https://www.facebook.com/kuboaki
* http://www.change-vision.com/

## YouTube動画

https://www.youtube.com/watch?v=LDv9_qaTV3w

```
This is episode 4 on Quality Shocking channel. The guest is Shin Kuboaki.

https://www.facebook.com/kuboaki
株式会社チェンジビジョン http://www.change-vision.com/

Object-oriented programming https://en.wikipedia.org/wiki/Object-oriented_programming
Functional programming https://en.wikipedia.org/wiki/Functional_programming
The Scala Programming Language https://www.scala-lang.org/
Ruby Programming Language https://www.ruby-lang.org/en/
class Array - Documentation for Ruby 2.6.0 https://docs.ruby-lang.org/en/2.6.0/Array.html
Ruby on Rails https://rubyonrails.org/
David Heinemeier Hansson (DHH) https://dhh.dk/
Sinatra http://sinatrarb.com/
Cookpad https://cookpad.com/
Twitter: From Ruby on Rails to the JVM https://www.youtube.com/watch?v=ohHdZXnsNi8
KonMari – Founded by Marie Kondo. https://konmari.com/
ISO 26262 https://en.wikipedia.org/wiki/ISO_26262
Mindstorms LEGO.com https://www.lego.com/en-us/mindstorms
What is LabVIEW? - National Instruments http://www.ni.com/en-us/shop/labview.html
Scratch - Imagine, Program, Share https://scratch.mit.edu/
Arduino - Software https://www.arduino.cc/en/Main/Software
Astah UML http://astah.net/editions/uml-new

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/4-kuboaki-take2/
```
