forking this repo to figure out how camera works


Android Audio and video Examples
===========

eclipse/ has the examples in eclipse project format, no longer updated.  Otherwise the examples are for android studio.

<b>AudioPlay</b> demos how to play a resource audio file and an audio file from any other location (ie filesystem, Internet, etc)

<b>AudioRecordTest</b> will record via the mic and then you can play it back.

<b>CameraPreview</b> only the Camera2 APIs and targets API 21+.  The code is broken up into a Preview class that just shows the camera preview in a surfaceview.  A capturePic class (that required the preview class) to take a picture. And there is a VideoClass as well.  This example is far from perfect, but works to show the separation in the classes.

<b>CameraXdemo</b> is a java version of the new cameraX from the androidX libraries.  Note, still alpha in some places.
<b>CameraXdemo_kt</b> is a kotlin version of the new CameraX androidX libraries.  Note, still alpha in some places.

<b>CameraXVideoDemo</b> is using java with the new CameraX for video recording. NOTE, this is using currently private APIs.  The video version of the cameraX APIs are not public yet.  So they may change without notice or simply stop working.  But it is working in RC01.
<b>CameraXVideoDemo_kt</b> is using kotlin with the new CameraX for video recording. NOTE, this is using currently private APIs.  The video version of the cameraX APIs are not public yet.  So they may change without notice or simply stop working.  But it is working in RC01.


<b>PicCapture1</b> shows how to write code to take a picture with either camera and camera2 apis.

<b>PicCapture2</b> hides most of the camera code in a cameraXpreview.  It has code for both camera and camera2 apis.

<b>PicCapture3</b> shows examples of how to take a picture with the intent.

<b>VideoCapture1</b> Uses an intent to record a video via the native recorder and then plays it in the app.

<b>VideoCapture2_1</b> Uses the camera2 to record videos and storages in public movie directory on the sdcard.  It has bottomNavView so you can switch to a player and see the videos you have recorded this session.

<b>VideoCapture3</b> shows how to record video with either Camera or Camera2 (API21+).  Note that using Camera in 21+ causes odd results like the video maybe upside down.

<b>VideoPlayA</b> shows and to play a video with a video view.

<b>YouTubeDemo</b> Shows how to use the youtube API and key.  This demo is still a work in progress.  https://developers.google.com/youtube/android/player/ 

<b>QRdemo</b> shows to to create and scan QR codes.  This uses zxing app and some of there code (included in project).
A link to where I got the code is https://github.com/zxing/zxing/tree/master/android-integration/src/main/java/com/google/zxing/integration/android 

<b>legacy/</b> are now abandoned examples and are no longer updated.

These are example code for University of Wyoming, Cosc 4730 Mobile Programming course.
All examples are for Android.
