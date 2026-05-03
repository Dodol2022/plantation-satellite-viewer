# Building and Running APK

## Prerequisites
Before you begin, ensure you have the following installed:
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Android Studio](https://developer.android.com/studio)
- [BlueStacks 5](https://www.bluestacks.com/)

## Steps to Build the APK
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Dodol2022/plantation-satellite-viewer.git
   cd plantation-satellite-viewer
   ```

2. **Open the Project in Android Studio**
   - Open Android Studio.
   - Choose 'Open an existing Android Studio project'.
   - Navigate to the cloned repository folder and select it.

3. **Build the APK**
   - Click on the `Build` menu in Android Studio.
   - Select `Build Bundle(s)/APK(s)` and then `Build APK(s)`.
   - Wait for the build process to finish.
   - You’ll see a notification upon completion with a link to locate your APK.

## Running on BlueStacks 5
1. **Install BlueStacks 5**
   - Download and install BlueStacks 5 from the official website.
   
2. **Launch BlueStacks 5**
   - Open BlueStacks after the installation.
   
3. **Install the APK**
   - Drag and drop the generated APK file onto the BlueStacks window or use the `Install APK` option in the sidebar.

4. **Run the App**
   - Once installed, find the app in BlueStacks, and click to launch it.
   
## Running on Android Studio Panda 2 Emulator
1. **Setup an Emulator**
   - Open Android Studio.
   - Go to the `AVD Manager` (Android Virtual Device Manager).
   - Create a new Virtual Device if you don’t have one set up.
   
2. **Start the Emulator**
   - Launch the emulator you created.
   
3. **Install the APK**
   - In Android Studio, click on the `Run` button or press `Shift + F10` to run the app directly on the emulator. Ensure the emulator is selected as the target device.
   
4. **Using ADB (Optional)**
   - Alternatively, you can use the ADB command to install the APK manually:
   ```bash
   adb install path/to/your.apk
   ```

## Conclusion
You should now be able to build and run the APK on both BlueStacks 5 and the Android Studio Panda 2 Emulator. If you encounter any issues, check the build logs for error messages and consult the documentation for BlueStacks or Android Studio for further troubleshooting.