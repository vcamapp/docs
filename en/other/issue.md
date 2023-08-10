# Bug Reports

### Issue Information

If you find an issue that isn't listed below, I'd appreciate it if you could contact us via the "Contact Us" section at the bottom of [VCam](https://vcamapp.com/).

[FAQ](faq.md)

### Version 0.2.2 - Latest

* Lip sync might stop working when connecting a microphone like AirPods while VCam is running.
  * **Solution:** Please re-select the lip sync mode after connecting the microphone. Alternatively, restart VCam.
* The camera's smile detection accuracy is low.
  * **Solution:** Microphone-based detection is more accurate, so I recommend selecting the microphone for lip sync mode.
* Combining the expression button with blinking and lip motion can distort the expression.
  * **Solution:** When creating the blend shape for the VRM file, make sure that combining A and Blink with other expressions won't cause distortions.
* Screen flickers in Zoom.
  * **Solution:** Reduce the camera's FPS or screen FPS in settings. (It's possible that the tracking or screen update processing isn't keeping up.)

<details>

<summary>Past Issues</summary>

#### Version 0.2.1

* The app crashes on devices without a built-in camera, like the Mac mini.

#### Version 0.1.2 - 0.2.0

* The screen goes blank when resizing the window.
  * **Solution:** Repeated resizing might display the screen. Until it's fixed, please use it at that screen size.
* The avatar's position might occasionally be off the screen when starting the app.
  * **Solution:** Press the "move to initial position" button.
* Camera tracking might occasionally not work.
  * **Solution:** Turn off the camera use in settings, then turn it back on.

#### Version 0.1.0 - 0.1.1

* The app might occasionally freeze, or crash upon closing.
* The video might freeze when invoking the virtual camera in browser functions like Google Meet.
  * **Solution:** Use another virtual camera like OBS's to relay this app's video.
* Camera tracking might not work on the initial startup.
  * **Solution:** Please restart the app.

</details>
