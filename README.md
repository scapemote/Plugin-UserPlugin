# Plugin-UserPlugin

This is a basic template for building DroidScript plugins using Android Studio

PLEASE NOTE: Plugins built with Android Studio will only work when built in RELEASE mode. Also, you cannot install the APK in the normal fashion.  It must be copied to the /DroidScript/Plugins folder on the internal sdcard and the DroidScript app restarted (an example Install.bat is included to help with this).

WARNING: If you use the Android support v4 libs in your plugin, you MUST use a version that matches the one used by DroidScript or crashes may occur!
This is the version currently used: https://mvnrepository.com/artifact/com.android.support/support-v4/24.0.0

An AIDE and Ant version of this example exists too. Please search on the DroidScript forum for more information:- https://groups.google.com/forum/#!forum/androidscript
