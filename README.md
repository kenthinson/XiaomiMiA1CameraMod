How to install:
1. Root phone. Don't ask me read this.
https://forum.xda-developers.com/mi-a1/how-to/root-mi-a1-oreo-8-0-disabling-ota-magisk-t3728654
2. Install my magisk module. 
https://github.com/kenthinson/XiaomiMiA1CameraMod/releases/download/2/v2.zip
3. Install Google Camera Mod by cstark27.
Original Post
https://forum.xda-developers.com/lg-v30/themes/cstark27-google-camera-mod-wide-angle-t3747263
Direct Link
https://drive.google.com/open?id=1KVJxQdVukqMR817QMzXBSbNRg5FX3yjs

Change log.

V2.0 - Dumped Open Camera in favor of Cinema4K for video and Google Camera for pictures. 
Dumped HEVC support as Cinima 4K does not support it.
I have only tested this with Android 8.1 Offical Rom. Custom roms may not work. If they dont ask for support for the driver from the rom developer I cant change the driver in somone elses custom rom.

V2 uses some of my original ideas and mixes them with other info I have found on xda. Thanks to sipollo for some of the ideas.

v1.0 - Initial Release.

## Description 
This modules is specifically designed for the Xiaomi Mi A1.
It replaces the media_profiles.xml located at /system/etc/ to enable the HEVC (High Efficiency Video Codec). This results in increased quality due to the newer codec at the same bitrate which was being used with H264.
In addition this module also enables Camera2API in build.prop and Enabled OpenCamera to access the telephoto camera for picutres and video recording.

