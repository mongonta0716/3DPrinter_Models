# 3DPrinter_Models
 A little collection of works

ちょっとした3DModelを公開しています。


## stackchan_sg90_metal_case_takao_version

ｽﾀｯｸﾁｬﾝ タカオ版をJLCPCBに依頼した時のファイルです。PLA用のモデルよりも穴径が大きくタップネジではなく、ボルト＋ナットで固定をするように設計しています。
**SG90用です。**

下記の点に注意してください。

- DesignSparkMechanical 6.0.1で編集しました。
- STLファイルとRSDOCXファイルです。
- 寸法はギリギリで設計しているので後で加工が必要な場合があります。<br>ステンレス316Mは硬いのでかなり苦労します。
- 歪んで届いたこともあります。その場合でも恐らく保証されません。（私も保証できません。）
- ミニルーター等があると後加工が少し楽になるかも？（怪我に注意です。）
- サーボはメタルギアのものでないと動かないと思います。
- 薄い部分があるので、レビュー時にリスクを許容するか確認されます。ご自身で決めて返信してください。<br>英語でメールが来ます。
- 猫耳HATはCoreS3のDINBASEでも使えるモデルですが、差すだけなのでなにか工夫が必要かもしれません。

発注するときは自己責任でお願いします。


## stackchan_sg90_case_takao_version

**SG90用です。**

レジンやPLAなど用のモデルです。

- DesignSparkMechanical 6.0.1で編集しました。
- STLファイルとRSDOCXファイルです。
- 寸法はギリギリで設計しているので後で加工が必要な場合があります。
- 歪んで届いたこともあります。その場合でも恐らく保証されません。（私も保証できません。）
- 薄い部分があるので、レビュー時にリスクを許容するか確認されます。ご自身で決めて返信してください。<br>英語でメールが来ます。
- 猫耳HATはCoreS3のDINBASEでも使えるモデルですが、差すだけなのでなにか工夫が必要かもしれません。

## strackchan_scs0009_case_takao_version

**Feetech SCS0009シリアルサーボ専用のモデルです。**

- DesignSparkMechanical 6.0.1で編集しました。
- STLファイルとRSDOCXファイルです。
- 寸法はギリギリで設計しているので後で加工が必要な場合があります。
- 歪んで届いたこともあります。その場合でも恐らく保証されません。（私も保証できません。）
- 薄い部分があるので、レビュー時にリスクを許容するか確認されます。ご自身で決めて返信してください。<br>英語でメールが来ます。

## stackchan_side_adapter_for_takao_ver

ｽﾀｯｸﾁｬﾝ タカオ版の左側の穴に取り付ける用のアダプターです。Groveケーブルを通している場合は使えません。

- side_base.stl<br>取り付ける土台です。改造用
- side_9hole.stl<br>

## stackchan-mini-for-vameter

[ｽﾀｯｸﾁｬﾝmini](https://x.com/mongonta555/status/1800142036345188758)用のSTLファイルです。
- M5StackのVAMeterの上だけを利用します。
- ブラケットは2つ出力してサーボとStack-chan_Takao_Baseを固定します。
猫耳と足はsg90用のものを66.6%で縮小してください。

### 必要な部品
- サーボ x 2 [Feetech FS0403](https://akizukidenshi.com/catalog/g/g114805/)
- M1.4ネジ(5～6mm) x 8
- [Stack-chan_Takao_Base SG90用](https://www.switch-science.com/products/8905)
- M2 x 4mm　x 1 pcs
- Grove-2.54mm-4P変換ケーブル(5～10cm)（20cmしかないので自作or改造の必要あり）[Grove - デュポン 変換ケーブル 20 cm（各5本セット）](https://www.switch-science.com/products/8305)

## stackchan_hat_ear_for_NekomimiLED

わししさんの[NekomimiLED](https://washishi.booth.pm/items/5686894)を分割せずにそのまま取り付けられる猫耳HATです。かなり適当にモデリングしたので参考程度に、、、
- Port.Cは使えなくなるので、サーボはPort.Aに接続してください。

### head_adapter_cat_v2.9.stl
透明フィラメント用の猫耳HATです。
- 前面は塞いでしまっているので透明フィラメントを使ってください。
- サポートはビルドプレートのみにしないと中空にならないので注意です。

### head_adapter_cat_v2.10.stl
不透明のフィラメント用の猫耳HATです。
- 耳の部分を少し薄くしているので強度が落ちています。
- サポートはビルドプレートのみの方がいいと思います。

# LICENSE

[Apache 2.0](https://github.com/mongonta0716/3DPrinter_Models/blob/master/LICENSE)
