A multi-threaded C++ library that plays video files supporting multiple codecs across platforms.
Easy to use, fast, responsive, abstract interface and minimal dependencies, you'll soon be wondering how you lived without it! ;)

Audio and Video interfaces are completely abstracted so the library can be used anywhere, regardless of what you use to display video frames and play audio samples (eg. OpenGL / OpenAL, Direct3D / DirectSound, SDL / SDL\_mixer, X11 / alsa ...)

The library can pre-cache video frames and decoded audio samples for maximum efficiency and smooth playback, even on single-cpu systems.

Currently, the library supports Theora On Windows, Mac, Linux and iOS and H.264 on Mac and iOS.
WebM, Android, Windows 8 and Windows Phone 8 support is planned.