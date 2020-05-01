
The code is still working in 2020 on Android 10.

Some observations:
- Running library module from Android Studio is not working using standard Run button. To install it use an item from Gradle pane library / install / installDebug.
- Feeding variables with simple and standard classes to remote function is working just fine. The problem is starting when trying to feed complex custom classes. You will get java.lang.reflect.InvocationTargetException due to different class loader in the plugin apk.


# Android Plugin Demo

Simple demonstration how to query plugin applications installed on device, access their resources, show Activity and invoke code directly from apk/dex.

## Links

English: [Android plugins or invoking code from another application](https://medium.com/@annimon119/android-plugins-or-invoking-code-from-another-application-1241427c504b)  
Russian: [Плагины в Android или выполняем код другого приложения](http://annimon.com/article/2168)
