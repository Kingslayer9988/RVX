# Debug Logging Guide

Follow these steps to enable debug logging and extract logs.

## Steps

1. **Enable Debug Logging**
   - Go to **Miscellaneous** settings in your app.
   - Enable both debug logging toggles.

2. **Set Up ADB**
   - Connect your device to your PC.
   - Ensure ADB (Android Debug Bridge) is set up. You can follow [this guide](https://developer.android.com/studio/command-line/adb) if you need assistance.

3. **Reopen the App**
   - Close and reopen the app to start fresh with the logging enabled.

4. **Extract Logs**
   - Open a terminal or command prompt.
   - Run the following command to filter the logs:

     ```bash
     adb logcat | grep --line-buffered "Extended" > log.txt
     ```

5. **Render the Component**
   - Navigate to the app and ensure that the component you want to log is displayed.

6. **Upload the Logs**
   - After reproducing the issue, find the `log.txt` file generated in your current directory.
   - Upload `log.txt` for analysis.

## Notes

- Make sure your device is in **developer mode** and **USB debugging** is enabled.