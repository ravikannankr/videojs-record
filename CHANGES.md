videojs-record changelog
========================

1.0.3 - 2015/12/20
------------------

- @alsar fixed wrong module require for browserify (#28)


1.0.2 - 2015/10/19
------------------

- Animated recording indicator (by @ikbensiep)
- Fixed `destroy`


1.0.1 - 2015/10/15
------------------

- fix AMD/Node/browser global dependency for videojs


1.0.0 - 2015/10/14
------------------

- Support for video.js 5
- Dropped support for video.js 4.x


0.9.3 - 2015/10/12
------------------

- Added translations for Afrikaans, German, Spanish, Finnish, Frisian, French, Galician, Italian, Portugese, Russian and Swedish


0.9.2 - 2015/10/06
------------------

- Bump minimum version for wavesurfer.js (1.0.44) and videojs-wavesurfer (0.9.9) for microphone updates (#12)
- Fix stop/getDevice in audio-only mode (#12)


0.9.1 - 2015/10/04
------------------

- Make sure bower and npm only download video.js v4.x (#15) because v5.0 is not supported yet (#6)
- Add `stopDevice` for disabling the webcam/microphone device (#12)
- Do something about new [mediastream deprecation warnings](https://developers.google.com/web/updates/2015/07/mediastream-deprecations) in Chrome 45 (#12)
- Fixed issue with missing `isChrome`


0.9.0 - 2015/09/25
------------------

- Support for libvorbis.js in audio-only mode (#8)
- Set default audio sample rate to 44100 (#7)


0.8.4 - 2015/08/27
------------------

- Examples fixes: wavesurfer changed domain name to wavesurfer-js.org


0.8.3 - 2015/07/30
------------------

- Add support for animated GIF recordings (#2)
- Both audio and video streams are now available when recording audio/video simultaneously in the Chrome browser (#4)
- Audio playback now works when recording both audio and video in the Chrome browser (#4)


0.8.2 - 2015/03/30
------------------

- Fix `debug` option


0.8.1 - 2015/03/30
------------------

- Remove duplicate `stopRecord` event trigger for image-only mode


0.8.0 - 2015/03/30
------------------

- Switch to `MRecordRTC` to enable recording audio/video blobs (in Firefox >= 29 only at time of this release)
- Hide fullscreen button in image-only example


0.7.0 - 2015/03/28
------------------

- Add support for images (#1)


0.6.0 - 2015/03/23
------------------

- Documentation fixes


0.5.0 - 2015/02/21
------------------

- Added `destroy` method for cleaning up
- Added `debug` option to control for console logging (in RecordRTC)


0.4.0 - 2015/02/19
------------------

- Compatibility fixes for Video.js 4.12.0


0.3.0 - 2015/02/11
------------------

- Added Dutch translation
- Disable controls during waveform rendering
- Add `deviceReady` event
- Documentation fixes


0.2.0 - 2015/01/07
------------------

- Bugfixes


0.1.0 - 2015/01/06
------------------

- Initial release