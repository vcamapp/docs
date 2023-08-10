# mocopi
Sonyのモーションキャプチャー「mocopi」との連携をサポートしています。

https://twitter.com/vcamapp/status/1689123753836572672

## 連携方法
1. mocopiのアプリを起動して、モーションキャプチャーを開始します。
手順はmocopiアプリに従ってください。

![image](https://github.com/vcamapp/docs/assets/8188636/a8ef381d-5af2-4bd5-8fa8-a919c74e09c8)

2. 右上のメニューから「設定」→「PC接続設定」を選びます。

<div>
![image](https://github.com/vcamapp/docs/assets/8188636/e305540d-4134-4b62-9e8f-f6730521037e)

![image](https://github.com/vcamapp/docs/assets/8188636/f0ed4c64-4aac-4a2a-aa43-b0d12d45b827)
</div>

3. VCamアプリを開いて、 ⚙️ ボタンをクリックし、「連携」タブからmocopiを有効にします。

![image](https://github.com/vcamapp/docs/assets/8188636/4ef7a7b3-f2e5-4664-ab36-8d4fa753bb44)

4. mocopiアプリの「PC接続設定」の「IPアドレス」に、3のVCamの設定画面に表示されているInfoのIPアドレスを指定して、OKを押します。
(ポート設定はそのままにしてください)

![image](https://github.com/vcamapp/docs/assets/8188636/6360d975-1ca2-4d80-907b-014b1ae217ee)

5. mocopiでモーションキャプチャーを開始すると、VCamに反映されます 🎉

## Tips / 活用テクニック

mocopiアプリはバックグラウンドでも動きます。そのため、[VCamMocap](https://tattn.fanbox.cc/posts/5134895)やiFacialMocapも同時に接続できます。

## トラブルシューティング

### VCamでアバターをクリックして選択できない

mocopiのトラッキングでの表示位置がズレている可能性があります。下記のボタンをタップして位置を修正してください。

![image](https://github.com/vcamapp/docs/assets/8188636/ac6f636c-f31f-4d24-9280-bf50d1feee66)

### mocopiアプリではトラッキング開始しているのにVCamに反映されない

iPhoneとMacが同じWiFiに繋がっているか確認してください。またセキュリティソフトなどでポート「12351」が塞がっていないか確認してください。

[BVH Sender](https://www.sony.net/Products/mocopi-dev/jp/downloads/DownloadInfo.html#BVH_Sender)を使うとmocopiなしで動作確認ができます (IPアドレスは127.0.0.1を指定してください)。このアプリのモーションがVCamに反映できる場合はネットワーク周りの設定に問題がある可能性が高いです。再度ご確認ください。

### mocopiとの連携を解除したい

設定画面の連携タブからmocopiを有効にするチェックを外します。その後、トラッキングタブでトラッキング方法を選択します。もし「手」が選択できないときはmocopi連携のチェックが外れているか確認してください。

![image](https://github.com/vcamapp/docs/assets/8188636/fc69e9c1-f8a3-4327-a5a2-6e067680f9c7)

### mocopiで前後に動けない

現在は左右の動きだけ反映される仕様にしています。前後の動きは将来のアップデートをお待ち下さい。
