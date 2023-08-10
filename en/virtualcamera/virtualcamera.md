# Virtual Camera

VCam has a camera function called a virtual camera.

By using this, you can get video conferencing apps such as Zoom and Google Meet to recognize VCam as a camera.

Currently, there are two types of virtual cameras:

- Virtual Camera (DAL)
    - Installed upon the first launch.
- New Virtual Camera (CameraExtension)
    - Currently, only supporters can use this feature.

The new virtual camera reduces the load on the Mac.

Also, Apple has announced that "Virtual Camera (DAL)" will no longer be supported in macOS 14.

[Apple's Announcement](https://developer.apple.com/videos/play/wwdc2022/10022/)

## Virtual Camera (DAL) Setup

Follow the alert that appears upon the first launch to install.

If you want to reinstall due to a problem or otherwise, click "Initial Setup" in the "VCam" menu.

If you want to uninstall the virtual camera, click "Uninstall Plugin" in the "VCam" menu.

## New Virtual Camera (CameraExtension) Setup

In the VCam settings, go to "Experimental Features" and check "Use New Virtual Camera".

<img alt="image" src="https://github.com/vcamapp/docs/assets/8188636/6319df68-f55b-438a-97c5-3556ed4b8260">

## How to Use the Virtual Camera

In the camera list of the application that uses a camera, "VCam" or "VCam - CameraExtension [Number]" will be displayed.

![zoom](https://github.com/vcamapp/docs/assets/8188636/288b4213-3320-4b36-b58a-ecc19c83eef3)

When you select "VCam", the "Virtual Camera (DAL)" is used, and when you select "VCam - CameraExtension", the "New Virtual Camera (CameraExtension)" displays the VCam video.

You can only use one or the other, so if you're using the "Virtual Camera (DAL)", please disable the "New Virtual Camera".