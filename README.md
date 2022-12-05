# MsxPs2MouseConverter
MSX PS/2マウス変換器
MSX PS/2 Mouse converter

## 概要
- PC用PS/2マウスをMSXのインテリジェントマウスとして使用するための変換器です
- 組み立てにはハンダ付けが必要です
- ケースは購入可能です、3Dプリンター用モデルも無料提供しています
- サポートはありません

![converter1](https://user-images.githubusercontent.com/102343209/205643273-2f765905-05a0-4b39-850b-36ef840f94fa.JPG)

## 動作
- 本機はMSXでよく使用されるであろう下記のモードに対応しています
  1. マウス (MSX互換モード)　　左クリック＋電源オン
  1. ジョイスティック　　　　　右クリック＋電源オン
  1. トラックボール　　　　　　ホイールクリック＋電源オン

- 起動時に押されていたボタンにより各モードを切り替えます
  - MSXロゴが出たらボタンは離してOKです
  - 設定はEEPROMに保存されるのでボタンを押さずに起動すると前回のモードとなります

- マウスモードのときホイール上下で感度(解像度)が5段階変化します

## 動作検証
- 以下のソフトで問題なく動作することを確認しました
  - 秘録 首斬り館 〜逐電屋藤兵衛〜（マウス）
  - スーパーグラフィックツール ダ・ビンチ（マウス）
  - 王家の谷（ジョイスティック）

## キット内容
- 変換基板 x1
- マイコン基板 (ソフトウェア書込み済) x1
- PS/2 ミニDIN 6pinコネクタ x1
- ピンヘッダ x2
- D-SUB 9ピンコントローラ用ケーブル x1
- ケース (オプション) 上下組 x1
  ※お届けする商品は画像のものと異なる場合があります

  ![parts](https://user-images.githubusercontent.com/102343209/205546597-d44bfb49-fa0e-4165-a02f-bfb4579cec4f.JPG)
  ![case](https://user-images.githubusercontent.com/102343209/205643322-3df91690-9fbb-4a0e-92fd-873f9b03fb1b.JPG) 

## 組立方法
- D-SUB 9ピンコントローラ用ケーブルの先端を剥き予備ハンダしておきます

  ![cable](https://user-images.githubusercontent.com/102343209/205546666-397d7a23-14c2-4252-88ee-3d656c710edc.JPG)

- 変換基板のシルクに書かれた色に合わせて9本のケーブルをハンダ付けします

![1st step](https://user-images.githubusercontent.com/102343209/205546684-318f367e-b6fe-4d5a-b3e4-3a6ba4c40f83.JPG)

- 部品の足などを使用してケーブルの抜け止めをハンダ付けします（キットには含まれません）
  - シルクの線を目安に黒い被膜がマイコン基板に干渉しないようにします

![2nd step](https://user-images.githubusercontent.com/102343209/205546717-61734072-591b-4666-b804-02b6615c139b.JPG)

- ミニDINコネクタとマイコン基板を取り付けます

![3rd step](https://user-images.githubusercontent.com/102343209/205546774-c15c048b-efa1-4cba-a366-791440be34b2.JPG)

- 裏面に飛び出したピンヘッダやコネクタの足はできるだけ短くカットします
  - ケースに入れない場合は絶縁テープなどを貼りショートしないようにします

![4th step](https://user-images.githubusercontent.com/102343209/205546794-ef5e0fdd-d42a-489d-af73-e1b310652ef6.JPG)

- ケースに入れます

![converter2](https://user-images.githubusercontent.com/102343209/205643459-5cd6bada-82fb-43eb-bec8-753ca8434380.JPG)

## 注意事項
- 先にマウスを変換器に接続してからMSXへ接続してください
- MSX接続中にマウスを抜き挿ししないでください、接続が切れてしまいます
  - 変換器自体をMSXに挿し直すことで復帰します

## ケースのプリント用データ

https://github.com/Retro-Do-MSX/MsxPs2MouseConverter/blob/9a62aeebc9353688a7a67238b351070e19405555/Models/MSXPs2MouseConverterCase.stl
