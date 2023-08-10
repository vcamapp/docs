# mocopi
VCam supports integration with Sony's motion capture software, "mocopi".

https://twitter.com/vcamapp/status/1689123753836572672

## How to Integrate
1. Launch the mocopi app and start motion capture. Follow the instructions provided in the mocopi app.

![image](https://github.com/vcamapp/docs/assets/8188636/a8ef381d-5af2-4bd5-8fa8-a919c74e09c8)

2. From the top-right menu, select "Settings" → "PC Connection Settings".

<div>
![image](https://github.com/vcamapp/docs/assets/8188636/e305540d-4134-4b62-9e8f-f6730521037e)

![image](https://github.com/vcamapp/docs/assets/8188636/f0ed4c64-4aac-4a2a-aa43-b0d12d45b827)
</div>

3. Open the VCam app, click the ⚙️ button, and enable mocopi from the "Integration" tab.

![image](https://github.com/vcamapp/docs/assets/8188636/4ef7a7b3-f2e5-4664-ab36-8d4fa753bb44)

4. In the "PC Connection Settings" of the mocopi app, specify the IP address displayed in the VCam settings screen in step 3 and press OK. (Leave the port settings as is)

![image](https://github.com/vcamapp/docs/assets/8188636/6360d975-1ca2-4d80-907b-014b1ae217ee)

5. When you start motion capture in mocopi, it will reflect in VCam 🎉

## Tips / Usage Techniques

The mocopi app works even in the background. Therefore, you can connect to [VCamMocap](https://tattn.fanbox.cc/posts/5134895) and iFacialMocap simultaneously.

## Troubleshooting

### Cannot select an avatar in VCam

The display position in mocopi's tracking might be offset. Tap the button below to adjust the position.

![image](https://github.com/vcamapp/docs/assets/8188636/ac6f636c-f31f-4d24-9280-bf50d1feee66)

### The mocopi app starts tracking, but it doesn't reflect in VCam

Ensure your iPhone and Mac are connected to the same WiFi. Check if port "12351" is not blocked by security software.

You can check the operation without mocopi using [BVH Sender](https://www.sony.net/Products/mocopi-dev/jp/downloads/DownloadInfo.html#BVH_Sender) (please specify the IP address as 127.0.0.1). If the motion from this app reflects in VCam, there might be an issue with the network settings. Please check again.

### Want to disconnect from mocopi

Uncheck "Enable mocopi" from the Integration tab in the settings. Then select the tracking method in the Tracking tab. If you can't select "Hand," ensure the mocopi integration checkbox is unchecked.

![image](https://github.com/vcamapp/docs/assets/8188636/fc69e9c1-f8a3-4327-a5a2-6e067680f9c7)

### Cannot move forward or backward in mocopi

Currently, only left and right movements are reflected. Please wait for a future update for forward and backward movements.