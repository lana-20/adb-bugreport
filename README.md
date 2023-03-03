# How do you use <code>adb bugreport</code> command to collect the logs?

A bug report contains device logs, stack traces, and other diagnostic information to help you find and fix bugs in your app. To capture a bug report from your Android device, use the [<code>adb bugreport</code>](https://developer.android.com/studio/debug/bug-report)  command. Follow these steps:
1. Connect the device to your machine: Use a USB cable or WiFi to connect the device to your machine. Make sure that USB Debugging is enabled on the device.
2. Start the ADB shell: Open a terminal or command prompt and navigate to the directory where the Android SDK is installed. Then use the <code>adb shell</code> command to start the ADB shell.
3. Collect the bug report: Within the ADB shell, use the <code>adb bugreport > bugreport.zip</code> command to collect a bug report from the device. This will create a <code>bugreport.zip</code> file on your machine that contains detailed logs, system data, and other information about the device and its current state.
4.  Examine the bug report: You can use a tool like Android Studio, Logcat Viewer or a text editor to examine the contents of the  <code>bugreport.zip</code> file and look for patterns or trends that might help you identify the cause of a crash, ANR, or other unexpected behavior.

Overall, using the <code>adb bugreport</code> command can be a useful command line tool to collect a comprehensive set of logs and diagnostic information from an Android device. This can be helpful when you are troubleshooting or debugging issues, or when you need to provide detailed information about the device to support or development teams.
