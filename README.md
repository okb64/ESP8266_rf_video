# ESP8266_rf_video
Allow the ESP8266 to generate RF video. Features a double framebuffer.  
This code is a modification of the amazing [apple II emulator](https://github.com/hrvach/espple) with PAL   
video output by Hrvoje Čavrak. It has functions to display lines and text with a font rom.  
It has only beentested on the wemos D1 mini with PAL video, but should work on NTSC two with the addition of #define NTSC on
[generate_video](wemosTv_display_dfb_clean/generate_video.c).  
The default code displays Hellow world! at thetop left corner of the screen.
