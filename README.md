# 3班　期末発表の目標
## 忖度じゃんけん
**１．やること**
- 人間とじゃんけんをして、人間の手の形を画像認識し、勝つかあいこだった場合に後出しで負けて忖度する
- 前後にモーションを付ける
- ex : 可能ならば相手が出してきたパターンを学習して傾向を推測し、最初から負けれるようにする。  
![gp](https://user-images.githubusercontent.com/72371743/99650051-4a9b0100-2a98-11eb-8ee5-c0f7d4982c02.png)  
左からグー,パーの時のアーム先端の予定
![t](https://user-images.githubusercontent.com/72371743/99650857-43c0be00-2a99-11eb-805b-4392df783d72.png)  
チョキの時のアーム先端予定(右：上からの図)
---

**２．面白い点**
- これを先輩、上司に使えば可愛がられるはず、、、(先生に使えば単位も!?)
- ロボットがわざと負けるという人間を馬鹿にした行為
- 
---
**３．使用する道具**
- crane_x7
- 自由自在に動かせる人間の手
---

**４．どういう構成のシステムを作るか**
1. アームの初期座標から指定した座標までいく
2. アームを開きトランプをつかむ
3. トランプを持ち上げる
4. 投げる（他の動きになるかも）





---
**５．考えられる問題**
- アームでトランプをつかめない（トランプが滑るなど)
  - アームの先端にゴム製のものをつける
- スケジュール通りに進まない
  - 予備日で帳尻合わせをする
--- 

**６．スケジュール**

**課題１** (10月25日まで)
- 指定した座標までアームを動かすプログラムの作成 /担当：伊奈、川鍋
- トランプをつかむ、離す動きのプログラムの作成(サンプル参考に) /担当：清原

**課題２** (11月1日まで)
- トランプをつかんだ後の動作のプログラムの作成  /担当：庄垣内、長谷川
- シミュレーター上で使うトランプ、台の作製（作り方調べる、TAに聞く）  /担当：藤原

**課題３** (11月8日まで)
- 課題1.2の動作のプログラムのマージする

**課題４** (11月12日まで)
- 一連の動作が安定してできるように調整

**課題５**(11月13日まで） 
- 中間発表の資料作り

![３スケジュール](https://user-images.githubusercontent.com/72371743/96401488-6e0b2b80-120e-11eb-940b-f50a8e18b90f.png)
