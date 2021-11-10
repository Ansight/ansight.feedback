# Description
Use Ansight to record, replay and analyse sessions for your Android device.

* 👀 Observe the runtime behaviour of your Android device. View, filter and analyse the device logs alongside it's display.
* 🎥 Record the screen and logs while using your device.
* 📼 Replay a device session, viewing its log data sequenced against the devices screen.

Ansight is still in (very) early preview and is envisaged as a tool to simplify communication between software users/testers and the engineering team.

Documentation is currently under construction at: https://docs.ansight.io

## Installation And Setup

 1. Download the attached Ansight.Studio.Mac package.
 2. Locate the package in your downloads.
 3. Right click on the package and select `Open`.
   a. You may receive a warning that Ansight is from an unknown developer. Please continue to run the installer.
 4. Run the installer.
 5. Open your Applications folder and double click on Ansight.Studio.Mac to launch Ansight. 

Finally, to use Ansight:

 * Locate your Android SDK installation. If you have Android Studio or Visual Studio Mac installed, Ansight should automatically do so.
 * Connect an Android device that has developer mode and USB debugging enabled. To enable this on your device, [please refer to this following article](https://developer.android.com/studio/debug/dev-options#enable).

## Known Limitations

 * Ansight is currently unsupported on Windows. If you would like to see this priories, [please visit the product roadmap] and give
 * Ansight is currently unsupported on Apple Silicon machines. It uses OpenCV for video streaming and replaying and support is not yet ready in OpenCVSharp for M1 Macs. This is actively being worked on and is being targeted for late 2021/early 2022.
 * When a devices display turns off, the video stream may not reconnected successfully when it is unlocked. To work around this:
   * Increase the automatic lock time of your device.
   * Disconnect and reconnect
 * Ansight is **not supported** on Android devices lower than API level 21.
