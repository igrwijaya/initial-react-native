## **Setup environment**

You will need Node, the React Native command line interface, Python2, a JDK and Android SDK (Android Studio).

 - Install Node, Python2, JDK
I recommend installing Node and Python2 via Chocolatey (https://chocolatey.org/install), a popular package manager for Windows.
after install Chocolatey, Open an Administrator Command Prompt (right click Command Prompt and select "Run as Administrator"), then run the following command:
```
choco install -y nodejs.install python2 jdk8
```
 

 - Install React Native CLI
 Run the following command in a Command Prompt or shell:
 ```
npm install -g react-native-cli
```

 - Install Android SDK
I recommend to download Android Studio (https://developer.android.com/studio/#downloads) to easiest setup Android SDK (bonus Android Studio as an IDE :D)

- Setup PATH for Android SDK
The React Native tools require some environment variables to be set up in order to build apps with native code.
Open the System pane under  **System and Security**  in the Windows Control Panel, then click on  **Change settings...**. Open the  **Advanced**  tab and click on  **Environment Variables...**. Click on  **New...**  to create a new  `ANDROID_HOME`  user variable that points to the path to your Android SDK.
by default, at the following location **c:\Users\YOUR_USERNAME\AppData\Local\Android\Sdk**.
You can find the actual location of the SDK in the Android Studio "Preferences" dialog, under **Appearance & Behavior** → **System Settings** → **Android SDK**.

## Run android app
```
npm run android-serve
```