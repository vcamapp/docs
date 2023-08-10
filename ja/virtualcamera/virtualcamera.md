# 仮想カメラ
VCamには仮想カメラと呼ばれるカメラ機能があります。

これを利用することで、ZoomやGoogle Meetなどのビデオ会議アプリなどでも、VCamをカメラとして認識させることができます。

仮想カメラには現在、2種類あります。

- 仮想カメラ (DAL)
    - 初回起動時にインストールされます。
- 新しい仮想カメラ (CameraExtension)
    - 現在はサポーターのみが使える機能です。

新しい仮想カメラのほうがMacの負荷が軽減されます。

また、「仮想カメラ (DAL)」は macOS 14 でサポート終了することがAppleにより発表されています。

https://developer.apple.com/videos/play/wwdc2022/10022/


## 仮想カメラ (DAL)の設定
初回起動時に表示されるアラートに従ってインストールしてください。

不具合などで再インストールしたい場合は、「VCam」メニューの「初期設定」をクリックしてください。

仮想カメラをアンインストールしたい場合、「VCam」メニューの「プラグインのアンインストール」をクリックしてください。

## 新しい仮想カメラ (CameraExtension)の設定
VCamの設定画面の「実験的な機能」から「新しい仮想カメラを使用する」をチェックしてください。

<img alt="image" src="https://github.com/vcamapp/docs/assets/8188636/6319df68-f55b-438a-97c5-3556ed4b8260">


## 仮想カメラの使い方
カメラを利用するアプリのカメラ一覧に「VCam」や「VCam - CameraExtension [番号]」が表示されます。

![zoom](https://github.com/vcamapp/docs/assets/8188636/288b4213-3320-4b36-b58a-ecc19c83eef3)

「VCam」を選ぶと、「仮想カメラ (DAL)」、「VCam - CameraExtension」を選ぶと「新しい仮想カメラ (CameraExtension)」でVCamの映像を表示できます。

どちらか一方しか利用できないため、「仮想カメラ (DAL)」を利用する場合は「新しい仮想カメラ」を無効にしてください。
