GeoFun Privacy Policy
=====================

GeoFun does not have the `INTERNET` permission, so it is impossible for the app to send any data anywhere.

GeoFun does save some data locally on your device:
* The user settings are saved to a local preference file unaccessible to other applications: sound on/off, stylus/thumb mode, units (km/miles), the "name" you typed to be associated with scores (default is "Anonymous") and the level and difficulty of the last game played.
* The top scores of the games are stored on the memory of your device.  This data is accessible to other applications.

None of this data is even remotely interesting, and it is not sent anywhere by GeoFun.

GeoFun does *not* *explicitly declare* the `READ_PHONE_STATE` permission.  This permission appears on the Play Store and on your device because this app was developped a really, really long time ago (2010), for one of the first versions of Android known as Cupcake (1.5).  On Cupcake, this permission didn't exist, and apps back then could access data like your phone's IMEI number, without any permission, if they so desired. When the next version of Android, Donut (1.6), was released, Google introduced this permission and required Android apps "targeting" Donut (or higher) to explicitly declare this permission, if they wanted to access phone state data.  Apps not specifying any "target version", like GeoFun, technically have this implicit permission.

However, GeoFun does nothing with the implicit `READ_PHONE_STATE` permission. The developer has no interest in any information this permission would grant access to, the app does not read any information to which this permission grants access, and GeoFun does not send any data over the internet. 

The developer would like to make the source code to GeoFun open source one day, but this is not currently the case.  The code is very old, and embarassing for the developer to publish.  Some cleanup would be required before publishing this. If you really want to know how GeoFun works, you are welcome to decompile the apk and study it.  The source code is not obfuscated.


