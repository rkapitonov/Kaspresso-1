//[kaspresso](../../index.md)/[com.kaspersky.kaspresso.device.apps](../index.md)/[AppsImpl](index.md)



# AppsImpl  
 [androidJvm] 

The implementation of the [Apps](../-apps/index.md) interface.

class [AppsImpl](index.md)(**logger**: [UiTestLogger](../../com.kaspersky.kaspresso.logger/-ui-test-logger/index.md), **context**: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), **uiDevice**: UiDevice, **adbServer**: [AdbServer](../../com.kaspersky.kaspresso.device.server/-adb-server/index.md)) : [Apps](../-apps/index.md)   


## Constructors  
  
|  Name|  Summary| 
|---|---|
| [AppsImpl](-apps-impl.md)|  [androidJvm] fun [AppsImpl](-apps-impl.md)(logger: [UiTestLogger](../../com.kaspersky.kaspresso.logger/-ui-test-logger/index.md), context: [Context](https://developer.android.com/reference/kotlin/android/content/Context.html), uiDevice: UiDevice, adbServer: [AdbServer](../../com.kaspersky.kaspresso.device.server/-adb-server/index.md))   <br>


## Types  
  
|  Name|  Summary| 
|---|---|
| [Companion](-companion/index.md)| [androidJvm]  <br>Content  <br>object [Companion](-companion/index.md)  <br><br><br>


## Functions  
  
|  Name|  Summary| 
|---|---|
| [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)| [androidJvm]  <br>Content  <br>open operator override fun [equals](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/equals.html)(other: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)| [androidJvm]  <br>Content  <br>open override fun [hashCode](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)  <br><br><br>
| [install](install.md)| [androidJvm]  <br>Brief description  <br><br><br><br><br>Installs an app via ADB.<br><br><br><br>Required Permissions: INTERNET.<br><br><br><br>  <br>Content  <br>open override fun [install](install.md)(apkPath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [installIfNotExists](install-if-not-exists.md)| [androidJvm]  <br>Brief description  <br><br><br><br><br>Installs an app via ADB only if packageName is not installed<br><br><br><br>Required Permissions: INTERNET.<br><br><br><br>  <br>Content  <br>open override fun [installIfNotExists](install-if-not-exists.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), apkPath: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [isInstalled](is-installed.md)| [androidJvm]  <br>Brief description  <br><br><br>Checks app is installed on device<br><br>  <br>Content  <br>open override fun [isInstalled](is-installed.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)  <br><br><br>
| [kill](kill.md)| [androidJvm]  <br>Brief description  <br><br><br>Kills the process of the app by the given packageName.<br><br>  <br>Content  <br>open override fun [kill](kill.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [launch](launch.md)| [androidJvm]  <br>Brief description  <br><br><br>Launches an app with given packageName.<br><br>  <br>Content  <br>open override fun [launch](launch.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), data: [Uri](https://developer.android.com/reference/kotlin/android/net/Uri.html)?)  <br><br><br>
| [openRecent](open-recent.md)| [androidJvm]  <br>Brief description  <br><br><br>Opens the app from the recent list by the description.<br><br>  <br>Content  <br>open override fun [openRecent](open-recent.md)(contentDescription: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [openUrlInChrome](open-url-in-chrome.md)| [androidJvm]  <br>Brief description  <br><br><br>Opens the given url on Chrome.<br><br>  <br>Content  <br>open override fun [openUrlInChrome](open-url-in-chrome.md)(url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)| [androidJvm]  <br>Content  <br>open override fun [toString](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)  <br><br><br>
| [uninstall](uninstall.md)| [androidJvm]  <br>Brief description  <br><br><br><br><br>Uninstalls an app via ADB.<br><br><br><br>Required Permissions: INTERNET.<br><br><br><br>  <br>Content  <br>open override fun [uninstall](uninstall.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [uninstallIfExists](uninstall-if-exists.md)| [androidJvm]  <br>Brief description  <br><br><br><br><br>Uninstalls an app via ADB only if it installed<br><br><br><br>Required Permissions: INTERNET.<br><br><br><br>  <br>Content  <br>open override fun [uninstallIfExists](uninstall-if-exists.md)(packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [waitForAppLaunchAndReady](wait-for-app-launch-and-ready.md)| [androidJvm]  <br>Content  <br>open override fun [waitForAppLaunchAndReady](wait-for-app-launch-and-ready.md)(timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), packageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>
| [waitForLauncher](wait-for-launcher.md)| [androidJvm]  <br>Content  <br>open override fun [waitForLauncher](wait-for-launcher.md)(timeout: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), launcherPackageName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))  <br><br><br>


## Properties  
  
|  Name|  Summary| 
|---|---|
| [targetAppLauncherPackageName](index.md#com.kaspersky.kaspresso.device.apps/AppsImpl/targetAppLauncherPackageName/#/PointingToDeclaration/)|  [androidJvm] open override val [targetAppLauncherPackageName](index.md#com.kaspersky.kaspresso.device.apps/AppsImpl/targetAppLauncherPackageName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>
| [targetAppPackageName](index.md#com.kaspersky.kaspresso.device.apps/AppsImpl/targetAppPackageName/#/PointingToDeclaration/)|  [androidJvm] open override val [targetAppPackageName](index.md#com.kaspersky.kaspresso.device.apps/AppsImpl/targetAppPackageName/#/PointingToDeclaration/): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)   <br>

