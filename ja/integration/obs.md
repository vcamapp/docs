---
description: Mac版のOBSと連携して、VCamの映像をOBSで表示することができます。
---

# OBSと連携する

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>


## VCam OBS Pluginを使う (おすすめ)

この方法は他の方法に比べて負荷を軽減できます。

{% hint style="info" %}
このプラグインを利用するためには、サポーター版のアプリで利用できる「実験的な機能」の中の「新しい仮想カメラを使用する」を有効にする必要があります。
{% endhint %}

### インストール

下記から最新版の .pkg ファイルをダウンロードし、ファイルを開いてインストールします。\
インストール後、OBS Studioは再起動してください。

{% embed url="https://github.com/vcamapp/obs-plugin/releases" %}

### 使い方

1. OBS Studioのソースの「+ボタン」をクリックし、「VCam」を選択して、ソースに追加します。
2. VCamアプリを開き、設定メニュー (歯車) から「実験的な機能」を選択し、「新しい仮想カメラを使用する」を有効にします。

<figure><img src="../.gitbook/assets/image (10).png" alt="" width="375"><figcaption></figcaption></figure>

3. OBS StudioにVCamの映像が映ります。

### クロマキー無しで背景を透明にする

VCamの背景選択から背景色を選択します。

<figure><img src="../.gitbook/assets/image (11).png" alt="" width="143"><figcaption></figcaption></figure>

そして、不透明度を0%にすると、OBS上の背景が透明になります。

<figure><img src="../.gitbook/assets/image (12).png" alt="" width="120"><figcaption></figcaption></figure>

## 映像デバイスからとしてVCamを利用する

1. ソースの追加ボタンから「映像キャプチャデバイス」を選択し、新規作成します。

<figure><img src="https://user-images.githubusercontent.com/8188636/154320879-44aa4caa-bd56-4775-9529-d54b9afc3c0c.png" alt="" width="375"><figcaption></figcaption></figure>

2. デバイスから「VCam - CameraExtension \[数字]」または「VCam」を選択します。

<figure><img src="https://user-images.githubusercontent.com/8188636/154321293-4dff954a-b815-44b9-9d9e-d1ea65aea34d.png" alt="" width="375"><figcaption></figcaption></figure>

※この時に事前にVCamを開いていれば、プレビューが表示されます。選択後にVCamを起動した場合は、デバイスのリストから別のデバイスを選んだ後にVCamを選び直すことでプレビューできます。

3. ソースをCtrl+クリックし、メニューから「フィルタ」を選択します。

![image](https://user-images.githubusercontent.com/8188636/154321674-cdf851d8-e375-4193-9481-f8f55ce91b64.png)

4. エフェクトフィルタの追加ボタンをクリックし、「クロマキー」を選択します。

![image](https://user-images.githubusercontent.com/8188636/154321774-076ca337-bb98-4911-bb56-359b3c07ee54.png)

5. VCam側の背景色に合わせて、色キーを設定すると背景色を消すことができます。

![image](https://user-images.githubusercontent.com/8188636/154322044-acf1ea4a-37b7-4b88-ae27-bcaa61a405e8.png)

6. (ウィンドウサイズによって余白が出ている場合は) エフェクトフィルタに「クロップ/パッド」を追加することで黒帯などを消すことができます。

![image](https://user-images.githubusercontent.com/8188636/154323204-aa42c68c-3749-49b5-9902-00c2346e953b.png)

これで自由自在にアバターとゲームの映像などを合成できるようになりました。\
VCamはアプリを最小化していても多くの機能は動作をするため、操作ウィンドウが不要な方は最小化してみてください。
