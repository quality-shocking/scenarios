# yksym

(書き方の例として[テンプレート](../../template/README.md)を参照してください)

## 収録場所/日時

* 時間: 2019-05-05 17:30-20:00
* 会議室: yksymさん職場
* 集合時間/場所: 2019-05-05 17:00 [ビック酒販 AKIBA店](https://goo.gl/maps/vJUegmvrcPT2cGkn9)
* 緊急連絡先: 090-3524-7064

## 番組の紹介

* ホスト/ゲスト「こんにちはー」
* ホスト「クオリティショッキングは毎回ゲストを迎えてソフトウェアの品質についてあーでもないこーでもないと話しあうチャンネルです。」

## ゲストの紹介

* ホスト「yksym(いくしむ)さんこんにちは。まずは簡単に自己紹介をしていただけますか？」
* ゲスト「こんにちは皆さん。yksymです。xxx 職場の痕跡が残らない範囲で自己紹介 xxx」

## yksymメモ

### 現在、個人(会社でも？)で取り組んでいるソフトウェアの品質向上への取り組み概要

* 品質とは、顧客の明示的・暗黙的期待にどれだけ応えているか
    * 品質 ≒ ((生産性 * 時間) \cup 期待) / 期待 でざっくり近似して考えてる

* そのソフトウェアを手段としてどんな課題を解決すべきか、何故解決したいのかを知り、まずはそれに一番効果を発揮するMVPを目指す
    * 相手の考えや意見(〜が欲しい)だけでなく、相手の状況を知ること(具体的な業務フローとか、目標数値とか、〜のせいで・・出来なくて困っているとか)
    * 捨てられるものは捨てて重要なものから手をつける
    * スクラム的なアプローチを取り、早く作って早く評価する

* 個人的に情報の整理や推敲の為にモデルを書いている
    * 詳しい動機とかは[ここ](../spec20180810/memo.md) に書いた
    * ただ、最近は性格的にキチッとしていて頭の中にZ3ソルバ詰んでる人ならわざわざモデルなんて書かなくても正しい判断をするような気がする（私は出来ない)

* 失敗談

```
過去色々な会社で関わったプロジェクトで作ったシステムの品質について悩まされたことは勿論ある

* 完成したと思った機能に問題があることが発覚し、大幅な手戻りが発生
* 顧客と合意した受け入れテストにパスしたが、クレームが発生し、終わったと思ったプロジェクトがゾンビのように不意に襲いかかる

品質とは？
-------

品質の定義

* SWEBOK Wiki "品質とはシステムが特定環境下においてステークホルダー達からの明示的な要求や暗黙的な期待に応えられる程度"(意訳)[1]
* バグ、いわゆるIEEE 982.1-2005 の defect（欠陥）の定義は、"設計者の認識の有無にかかわらず、すべての成果物において要件定義の誤り、仕様設計の誤り、プログラミングの誤り、システム構築の誤りなどにより「期待される結果」と乖離があるために、何かしらの対策・対応が必要と考えられる現象またはその原因。"[2]
* 要求にスケジュールや金額面も含まれることを加味すると、そのプロジェクトが成功したかどうか、にかなり近い
```

## (YouTubeページ下へ付記する)リンク集

* http://yksym.github.io/
* https://github.com/yksym

## YouTube動画

https://www.youtube.com/watch?v=khGzBTg--1E

```
This is episode 5 on Quality Shocking channel. The guest is Yksym.

http://yksym.github.io/
https://github.com/yksym

Formal specification https://en.wikipedia.org/wiki/Formal_specification
Minimum viable product (MVP) https://en.wikipedia.org/wiki/Minimum_viable_product
Software Engineering Body of Knowledge (SWEBOK) https://en.wikipedia.org/wiki/Software_Engineering_Body_of_Knowledge
Unified Modeling Language (UML) https://en.wikipedia.org/wiki/Unified_Modeling_Language
Specification by example (SBE) https://en.wikipedia.org/wiki/Specification_by_example
IEEE 982.1-2005 https://standards.ieee.org/standard/982_1-2005.html
Stakeholder https://en.wikipedia.org/wiki/Stakeholder_(corporate)
ソフトウェア要求 https://www.amazon.co.jp/dp/4891003545

Scenario in Japanese: https://github.com/quality-shocking/scenarios/blob/master/scenarios/5-yksym-take1/
```
