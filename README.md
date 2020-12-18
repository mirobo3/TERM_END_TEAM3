# 3班　期末発表の目標
## 忖度じゃんけん
**１．やること**
- 人間とじゃんけんをして、人間の手の形を画像認識し勝つかあいこだった場合に負けて忖度する
- 前後にモーション(最初は～や悔しがってあげるなど)を付ける
- ex1 : 人間がグーチョキパー以外の手を出してきた時にも対応できるようにする
- ex2 : 可能ならば相手が出してきたパターンを学習して傾向を推測し、最初から負けれるようにする  
![gp](https://user-images.githubusercontent.com/72371743/99650051-4a9b0100-2a98-11eb-8ee5-c0f7d4982c02.png)  
- 左からグー,パーの時のアーム先端の予定  
![t](https://user-images.githubusercontent.com/72371743/99650857-43c0be00-2a99-11eb-805b-4392df783d72.png)  
- チョキの時のアーム先端予定(右：上からの図)  
---

**２．面白い点**
- ロボットが忖度する点
- ロボットがわざと負けるという人間を馬鹿にした行為
- これを先輩,上司に使えば絶対に可愛がられるはず！

---
**３．使用する道具**
- crane_x7
- realsense
- 問題なくじゃんけんができる人間の手
---

**４．どういう構成のシステムを作るか**
1. グー、チョキ、パーのどれかのポーズをとる（この時人間も一緒にじゃんけんをする）
2. realsenseで人間の手のポーズを認識する
3. 画像データから勝ちorあいこの時、人間の手に負ける手を選ぶ
4. 負ける手のポーズをとる
<img width="620" alt="システム図改" src="https://user-images.githubusercontent.com/72371850/99904779-893af080-2d10-11eb-80a4-60111a286d8a.png">

- 認識
![スクリーンショット (2)](https://user-images.githubusercontent.com/72371743/100577874-7f267c80-3324-11eb-981f-c1ede2f6b6ef.png)
- 認識テストyoutube  
https://www.youtube.com/watch?v=Ps_Jx4aETns&ab_channel=%E5%8B%95%E7%94%BB%E4%BF%9D%E7%AE%A1%E5%BA%AB


---
**５．考えられる問題**
- 人間が出した手のポーズを正確に認識して正しい動きができるか

- スケジュール通りに進まない
  - 予備日で帳尻合わせをする
  - メンバー間で連絡を密にとる
--- 

**６．スケジュール**

目標、12月14日までにほぼ完成させること
- 発表日　講義最終週（12月21日）

  - realsense のサンプルコードの理解（11月29日まで）
  - グー、チョキ、パーの手の動きのプログラム作成（11月29日まで）担当 清原
  - 最初はグーのモーションのプログラム作成 (11月29日まで) 担当 庄垣内
  - 悔しがるなどのモーションのプログラム作成 (11月29日まで) 担当 長谷川
  - realsense での画像認識  (11月29日まで) 担当 伊奈
  - mainノードの作成 (12月6日まで) 担当 藤原
  - realsenseからデータを受け取るプログラムを作る（12月6日まで）担当 川鍋
  - 実機動作完成（12月13日まで）
  - 資料作成（12月17日まで）

![2020-11-27 (2)](https://user-images.githubusercontent.com/72371137/100402524-d36cfa80-309f-11eb-9e67-187c0be3b329.png)
