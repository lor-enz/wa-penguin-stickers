# WhatsApp Penguin Stickers

My personal sticker app for the WA Messenger with Penguin Stickers. 
Also includes Buttons to add the Stickers to Signal or Telegram.

This is a fork of the [official WhatsApp Stickers App Template](https://github.com/WhatsApp/stickers)
There are technical Changes that improve the Android app. And there are changes to include sticker content I made myself.

Only the Android App is modified. The iOS App is untouched. Both Apps are in one Repo and I'd like to diverge from the original repo as little as possible that's why the iOS app is still present.

More info about my stickers is available at [lorenz.kiwi/sticker](https://www.lorenz.kiwi/sticker/)

[**Install it from the Play Store**][play-store-link]

![alt text][screenshot-with-frame]

[screenshot-with-frame]: https://www.lorenz.kiwi/wp-content/uploads/2021/02/scrnsht2_pixel_frame_270x512.png "Burgis Bapperl Screenshot"



## Technical Changes

### Boring Stuff

Brought the Android Version up to date to current Versions and Google Policies.

- Upgraded Android Gradle Plugin from 4.1.3 -> 7.4.0
- Changed compileSdkVersion from 30 -> 31
- Changed targetSdkVersion from 30 -> 31
- Added android:exported tag to EntryActivity in AndroidManifest.xml  

### Exciting Stuff

Includes an "Add to Telegram" Button and an "Add to Signal" Button. The buttons are **not** just hardcoded in. The contents.json can easily be modified to replace the my sticker content with other sticker content. The Buttons are connected to the information in the contents.json that now have two extra Strings: *telegram\_link* and *signal\_link*


## License

The Software excluding the Sticker images is BSD licensed, as found in the LICENSE-code file.

The Sticker images follow a different license, as found in the LICENSE-images file 


[play-store-link]: https://play.google.com/store/apps/details?id=kiwi.lorenz.stickers