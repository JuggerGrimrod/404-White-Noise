# 404: File Not Found (White-Noise Edition) v1.0.0 (@ /JuggerGrimrod/404-White-Noise)

## This Git repository contains markup, image, style and audio file assets for a stand-alone, cross-browser, device-agnostic 404 page.

This creation is a throwback, meant to emulate the audiovisual result of tuning an analog tv set to a channel which contains no received transmissions.  So when your users end up on a 404 page, they'll get the 1970s equivalent of "file not found" in the form of tv-snow and white-noise.

The audio-defaulted-on is an **intentional feature**, and for the sake of those who may be **wildly upset** by that intentional feature, a mute/unmute toggler button is included in the UI.

This 404 demo runs on the **jQuery 1.12.0** library, and contains **.mp3, .ogg and .wav** audio files.  

You can switch between (default) black-and-white tv-static and color tv-static backgrounds by commenting/uncommenting lines 6-7 of **/css/style.css**. 

A Google Font call to "Russo One" is included, as are generic media queries for responsive display (note: these media queries are *very* generic, and are not meant to cover every resolution on every device on Earth - a URL is provided on line 84 of **/css/style.css** if you need to go that route and aren't sure how to manage it).

The js/jQuery for this demo is in-line within the HEAD section of the **/index.html** file.  The script is not extensive, so it wasn't ported into a stand-alone .js file.  Feel free to change that for your own purposes.

Line 27 of **/index.html** contains a commented-out line of jQuery - this line, when uncommented, will fade the background static image out of display 5 seconds after it fades into display, and any additional functionality which you may want to append should be placed on line 28, within the scope of the *whiteNoise* function.

This demo also includes a generic 404 favicon.ico file and favicon call in **/index.html**, plus a javascript "back" button, so users can click that or their browser "back" button to return to the previous page in their window.history (expressed as **window.history.back()**).

HTML5 audio autoplay is not allowed on mobile platforms, so when viewing this on a mobile device, you will get the video experience without audio.

Standard volume control icons (i.e. volume on, volume muted) are not included in version 1.0.0, but may be added to future versions of this demo.

That's it.  Enjoy!

## Jugger Grimrod's 404: File Not Found (White-Noise Edition) README.md file v1.0 

### Free to all via GNU General Public License v3.0.
