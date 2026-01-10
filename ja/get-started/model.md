# アバターの読み込み

## VCam

メニューの「ファイル」からモデルを読み込めます。現在はローカルにある [VRM ファイル](https://vrm.dev/) または [VRoid Hub](https://hub.vroid.com/) のモデルに対応しています。

<figure><img src="../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

モデルファイルをドラッグ&ドロップして、読み込むこともできます。

ローカルの VRM ファイルを読み込んだ場合は、アプリ再起動時に自動的にそのモデルを読み込みます。VRoid Hub のモデルは自動設定されないため、再設定してください。

### FBX や MMD ファイルを読み込みたい

Unity を使うと、多くのファイルを VCam で読込み可能な VRM 形式に変換できます。

方法は下記のドキュメントなどを確認してください。

{% embed url="https://vrm.dev/univrm1/vrm1_tutorial/index.html" %}

## VCam2D

メニューの「ファイル」もしくはドラッグアンドドロップで Live2D Cubism モデルを読み込めます。下記の構成になっているフォルダを選択してください。

```
- モデルフォルダ
  - <モデル名>.moc3
  - テクスチャフォルダ
    - テクスチャ画像1.png
  - その他のファイル (physics3.json, motions, expressions フォルダなど)
```
