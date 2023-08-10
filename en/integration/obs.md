---
description: You can display VCam video on OBS by integrating with the Mac version of OBS.
---

# Integrate with OBS

![OBS Studio](https://github.com/vcamapp/docs/assets/8188636/d76b22c8-84de-4b10-af07-cc757519b1cf)

## Using the VCam OBS Plugin (Recommended)

This method reduces the load compared to other methods.

{% hint style="info" %}
To use this plugin, you need to enable the "Use new virtual camera" option found under "Experimental Features" which is available in the supporter version of the app.
{% endhint %}

### Installation

Download the latest .pkg file from the link below and open the file to install.\
After installing, please restart OBS Studio.

{% embed url="https://github.com/vcamapp/obs-plugin/releases" %}

### How to use

1. Click on the "+" button under OBS Studio's sources, select "VCam" and add it to the sources.
2. Open the VCam app, go to the settings menu (gear icon), select "Experimental Features", and enable "Use new virtual camera".\
   ![image](https://github.com/vcamapp/docs/assets/8188636/6f52a888-084a-4be2-867a-f7fcc67a1f75)\

3. VCam's video will now appear in OBS Studio.

### Making the background transparent without chroma key

Choose a background color from VCam's background selection.

<figure><img src="https://github.com/vcamapp/docs/assets/8188636/924e0d7a-adea-4e94-9205-8e0967d93d7f" alt="" width="188"><figcaption></figcaption></figure>

By setting the opacity to 0%, the background on OBS becomes transparent.

<figure><img src="https://github.com/vcamapp/docs/assets/8188636/6de53ef1-68d6-4029-98ac-6601fbf7508b" alt="" width="188"><figcaption></figcaption></figure>

## Using VCam as a Video Device

1. From the "Add Source" button, select "Video Capture Device" and create a new one.

<figure><img src="https://user-images.githubusercontent.com/8188636/154320879-44aa4caa-bd56-4775-9529-d54b9afc3c0c.png" alt="" width="375"><figcaption></figcaption></figure>

2. From devices, select "VCam - CameraExtension \[number]" or "VCam".

<figure><img src="https://user-images.githubusercontent.com/8188636/154321293-4dff954a-b815-44b9-9d9e-d1ea65aea34d.png" alt="" width="375"><figcaption></figcaption></figure>

* If you have VCam opened in advance, a preview will be displayed. If you start VCam after selecting, choose another device from the device list and reselect VCam to preview.

3. Ctrl+click on the source, and select "Filters" from the menu.

![image](https://user-images.githubusercontent.com/8188636/154321674-cdf851d8-e375-4193-9481-f8f55ce91b64.png)

4. Click on the "Add Effect Filter" button and select "Chroma Key".

![image](https://user-images.githubusercontent.com/8188636/154321774-076ca337-bb98-4911-bb56-359b3c07ee54.png)

5. Match the color key to VCam's background color to remove the background.

![image](https://user-images.githubusercontent.com/8188636/154322044-acf1ea4a-37b7-4b88-ae27-bcaa61a405e8.png)

6. If there are black bars (depending on the window size), you can remove them by adding "Crop/Pad" to the effect filters.

![image](https://user-images.githubusercontent.com/8188636/154323204-aa42c68c-3749-49b5-9902-00c2346e953b.png)

You can now freely combine avatars and game footage.\
Even if you minimize the VCam app, many features will still work. If you don't need the operation window, try minimizing it.
