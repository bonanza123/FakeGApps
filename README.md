# FakeGApps by thermatk

Used in combinaton with [µg GmsCore](https://github.com/microg/android_packages_apps_GmsCore) to enable Google Cloud Messaging (GCM) and much more.

This tutorial describes only the installation process to get GCM working. The also avaiable Google Play Store replacement Blankstore is not discussed here.

## Installation for Android with root access and without Gapps

* Install Xposed 
    * For Lollipop (5.1 and 5.1.1) from http://forum.xda-developers.com/xposed/super-alpha-posted-permission-xposed-t3072979

    * For Lollipop (5.0) from http://forum.xda-developers.com/showthread.php?t=3034811

    * For version below Lollipop using Xposed installer from http://repo.xposed.info/module/de.robv.android.xposed.installer

* Install this FakeGApps module (see 'releases') and enable it in Xposed Installer under 'Modules'
* Install FakeStore from http://own.darkcloud.ca:90/Android-Builds/ 
* Install latest GmsCore build 'play-services-core-debug.apk' from http://files.brnmod.rocks/apps/GmsCore/Latest/

Note: to enable GCM e.g for messaging apps like Threema or Textsecure, you have to update / install the same apk once again to allow them to obtain the GCM related permissions.

GCM can be tested using e.g. https://play.google.com/store/apps/details?id=com.firstrowria.pushnotificationtester&hl=en which is also downloadble from http://apps.evozi.com/apk-downloader/?id=com.firstrowria.pushnotificationtester


## Untested ways to remove Gapps

The procedure described [here](http://hex.ro/wp/blog/removing-gapps-from-cyanogenmod-11/) for removing Gapps from CM11 should also work for other ROMs where Gapps has been installed using a flashable zip. 