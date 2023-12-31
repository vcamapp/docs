# 不具合情報

### 不具合情報

下記に記載のない不具合を発見した方は、[VCam](https://vcamapp.com/)の下部の「お問い合わせ」から連絡していただけると嬉しいです。

[よくある質問](faq.md)

### バージョン 0.2.2 〜 最新版

* VCam起動中にAirPodsなどのマイクを接続するとリップシンクが動かなくなることがある
  * 【対処方法】 マイク接続後にリップシンクの方式を再選択してください。もしくは、VCamを起動してください。
* カメラでの笑顔の判定の精度が低い
  * 【対処方法】 マイクでの判定のほうが精度が高いため、リップシンクの方式をマイクにすることをおすすめします。
* 表情ボタンと瞬きや口パクを組み合わせると表情が崩れる
  * 【対処方法】 VRMファイルのブレンドシェイプ作成時にAとBlinkを他の表情と組み合わせても崩れないようにしてください。
* Zoomで画面がちらつく
  * 【対処方法】 カメラのFPSや画面のFPSを設定で下げてください。 (トラッキングや画面の更新処理が間に合っていない可能性があります)

<details>

<summary>過去の不具合</summary>

### バージョン 0.2.1

* Mac mini等の標準のカメラが搭載されていないデバイスでアプリがクラッシュする

### バージョン 0.1.2 〜 0.2.0

* ウィンドウをリサイズすると画面が映らなくなる
  * 【対処方法】 何度かリサイズしていると画面が表示されます。修正まではその画面サイズでご利用ください。
* アプリを起動するとアバターの位置が画面外になることがある
  * 【対処方法】 初期位置に移動ボタンを押してください
* たまにカメラトラッキングが動かない
  * 【対処方法】 設定タブでカメラの使用をOFFにした後、ONに戻してください

### バージョン 0.1.0 〜 0.1.1

* アプリがまれに固まる、アプリ終了時にクラッシュする
* Google Meetなどのブラウザの機能で仮想カメラを呼び出すと映像が固まる場合がある
  * 【対処方法】 OBSの仮想カメラなどを経由して本アプリの映像を送るようにしてください
* 初回起動時にカメラトラッキングが動かない
  * 【対処方法】 アプリを再起動してください

</details>
