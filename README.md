# Ghost Stickers — OTA endpoint

Ghost Emoji sticker pack (com.dimaseinc.ghoststickers). The app checks
version.json on launch and offers in-app updates when versionCode is newer.

- version.json — current release manifest (versionCode 3 / 1.2)
- ghost-stickers-1.2.apk — current release APK

To ship a new version: build it, drop the APK in here as
ghost-stickers-<version>.apk, bump versionCode/versionName/apkUrl in
version.json, push. The app picks it up on next launch.
