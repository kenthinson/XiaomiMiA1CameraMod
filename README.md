Change log.

V2.0 - Dumped Open Camera in favor of Cinema4K for video and Google Camera for pictures. 
Dumped HEVC support as Cinima 4K does not support it.

v1.0 - Initial Release.

## Description 
This modules is specifically designed for the Xiaomi Mi A1.
It replaces the media_profiles.xml located at /system/etc/ to enable the HEVC (High Efficiency Video Codec). This results in increased quality due to the newer codec at the same bitrate which was being used with H264.
In addition this module also enables Camera2API in build.prop and Enabled OpenCamera to access the telephoto camera for picutres and video recording.

Example of telephoto video recording in 4k can be found on youtube
https://youtu.be/SYDZ_PLQWpo
