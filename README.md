# Bluetooth Chat — Mobile Build

This project is intended to be opened in AndroidIDE on an Android phone.

## Build on phone
1. Install AndroidIDE.
2. Extract this ZIP.
3. In AndroidIDE choose Open Existing Project and select the extracted `BluetoothChat_MobileBuild` folder.
4. Allow Gradle to sync and download dependencies.
5. Build the project and choose the debug APK.
6. Install the APK on two Android phones.
7. Pair the phones in Android Bluetooth settings, then use the app to connect and send messages.

Internet is needed initially to download Android/Gradle dependencies. After the APK is installed, the Bluetooth chat itself does not need internet.

## Notes
- This is a starter Bluetooth Classic text-chat app.
- Android 12+ asks for nearby Bluetooth permissions.
- Pair the phones first in system Bluetooth settings.
