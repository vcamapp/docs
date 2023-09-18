# 仮想カメラ設定

VCamには仮想カメラと呼ばれるカメラ機能があります。

これを利用することで、ZoomやGoogle Meetなどのビデオ会議アプリなどでも、VCamをカメラとして認識させることができます。



## 仮想カメラの設定

VCamの設定画面の「仮想カメラ」で動作状況の確認や仮想カメラのインストールやアンインストールができます。

![image](https://github.com/vcamapp/app/assets/8188636/a39c5c68-7215-42a4-bcf4-8a2f97cfb198)

インストールやアンインストール後はMacの設定の「プライバシーとセキュリティ」で「許可」をクリックし設定を反映させる必要があります。

![Macの設定](https://github.com/vcamapp/app/assets/8188636/65b3804d-7108-4e1d-9ff7-dd02ff105a38)

{% hint style="info" %}
現在のmacOSではプラグインのインストールやアンインストール時にMacの再起動が必要になる場合があります。正常に動作しない場合などはMacを再起動してください。
{% endhint %}



## 仮想カメラの使い方

カメラを利用するアプリのカメラ一覧に「VCam - CameraExtension \[番号]」が表示されます。

![zoom](https://github.com/vcamapp/docs/assets/8188636/288b4213-3320-4b36-b58a-ecc19c83eef3)

「VCam - CameraExtension」を選ぶと、VCamの映像を表示できます。



<details>

<summary>過去のドキュメント (VCam 0.10.1以下用)</summary>

仮想カメラには現在、2種類あります。

* 仮想カメラ (DAL)
  * 初回起動時にインストールされます。
* 新しい仮想カメラ (CameraExtension)
  * 現在はサポーターのみが使える機能です。

新しい仮想カメラのほうがMacの負荷が軽減されます。

また、「仮想カメラ (DAL)」は macOS 14 でサポート終了することがAppleにより発表されています。

https://developer.apple.com/videos/play/wwdc2022/10022/

## 仮想カメラ (DAL)の設定

初回起動時に表示されるアラートに従ってインストールしてください。

不具合などで再インストールしたい場合は、「VCam」メニューの「初期設定」をクリックしてください。

仮想カメラをアンインストールしたい場合、「VCam」メニューの「プラグインのアンインストール」をクリックしてください。

</details>
