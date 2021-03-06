README
======

Transistor - Radio app for Android
----------------------------------

**Version 1.1.x ("Running Gun Blues")**

Transistor is a bare bones app for listening to radio programs over the internet. The app stores stations as files on your device's external storage. It currently understands streams embedded within m3u and pls links.

Transistor is free software. It is published under the [MIT open source license](https://opensource.org/licenses/MIT). 

Install Transistor
------------------
Get the latest release on [Google Play](https://play.google.com/store/apps/details?id=org.y20k.transistor).

Get an APK here on [GitHub](https://github.com/y20k/transistor/releases).

How to use Transistor
---------------------
### How to add a new radio station?
The easiest way to add a new station is to search for m3u streaming links and then choose Transistor as a your default handler for m3u. You can also tap the (+) symbol in the top bar and paste in m3u links directly.

### How to play back a radio station?
Tap the big Play button ;).

### How to stop playback?
Tap the big Stop button or unplug your headphones or swipe off the notification from the lock screen.

### How to rename or delete a station?
The rename and delete options can be accessed both from the list of stations and from the now playing screen. Just tap on the three dots symbol. You can manage the list of stations also from a file browser (see next question).

### Where does Transistor store its stations?
Transistor does not save its list of stations in a database. Instead it stores stations as m3u files on your device's external storage. Feel free to tinker with those files using the text editor of your choice. The files are stored in /Android/data/org.y20k.transistor/Collection.

### How do I backup and transfer my radio stations?
Transistor supports Android 6's [Auto Backup](http://developer.android.com/about/versions/marshmallow/android-6.0.html#backup) feature. Radio stations are always backed up to your Google account and will be restored at reinstall. On devices running on older versions of Android you must manually save and restore the "Collection" folder.

### Why does Transistor not have any setting?
There is nothing to be set ;). Transistor is a very simple app. Depending on your point of view "simple" is either great or lame.

Which Permissions does Transistor need?
---------------------------------------
### Permission "INTERNET"
Transistor streams radio stations over the internet.

### Permission "READ_EXTERNAL_STORAGE"
Transistor needs access to images and photos to be able to offer an option to customize radio station icons.
