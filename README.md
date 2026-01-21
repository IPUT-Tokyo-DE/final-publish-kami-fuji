[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/bmitlLjS)
# Jump Clime!!

## ゲームの内容
下から迫ってくるマグマをよけ、体力を保持しながらゴールを目指すゲームです。

![画面イメージ](docs/images/game_image01.png)

## 操作説明
例
WASDキー ：前後左右の移動
Spaceキー：ジャンプする。ジャンプの高さは自身のスピードに由来します。
Shiftキー：ダッシュします。ダッシュしている際はジャンプ力も高くなります

# レポート
## 1：企画書
ゲームとして視点の切り替えも行いたかったが、今回は四方を壁でかこう必要があったため、視点の切り替えを行わないようにした。
ゲーム性はシンプルにしようと思い敵や複雑な要素は追加しないようにした。
しかし、実装しようと思っていた処理である「ジャンプをすると足場のOn/Offが切り替わる」というギミックを実装することができなかったことは悔やまれる。
<img width="1920" height="825" alt="スクリーンショット 2026-01-21 234351" src="https://github.com/user-attachments/assets/7108543d-23d2-4d5e-acd5-66d6b3ba7143" />
上記は、実装している「上に乗るとプレイヤーを上昇させる足場」の写真

## 2：アピールポイント
ゲームの難易度を上げすぎず、下げすぎないように適切に調整するようにした。
具体的には、ダメージエリアの上昇スピードやダメージ数値、ジャンプパッドの上昇量やプレイヤー自身のジャンプ力、スピードなどを適切な数値に調整することで難易度の調整を図った。

## 3：使用したアセット
Free Lowpoly Scifi Objects
[https://assetstore.unity.com/ja-JP/publishers/107245](https://assetstore.unity.com/packages/3d/environments/sci-fi/free-lowpoly-scifi-objects-339074)

Lava Flowing Shader
[https://assetstore.unity.com/account/assets](https://assetstore.unity.com/packages/vfx/shaders/lava-flowing-shader-33635)

Robot Kyle | URP
https://assetstore.unity.com/packages/3d/characters/robots/robot-kyle-urp-4696

## 4：AI使用に関して
今回のプロジェクトでは以下の点でAIを使用した
・プレイヤーを上昇させるスクリプトのヒント、訂正
・プレイヤーのカメラ移動や視点変更に関するスクリプトの開発補助、訂正
・ダメージを与えるエリアを作成するスクリプトの訂正
・すべてのスクリプトの整頓と視認性の向上
### うまくいったこと




