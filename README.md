# CoreAudio
CoreAudio stand-alone for Windows. Make it easier to use for OBS. Otherwise you have to install iTunes entirely as Apple reworked their installation package for Windows 10 and later.

Minimum required files:

```
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreFoundation.resources\*"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreMedia.resources\*"
"C:\Program Files\Common Files\Apple\Apple Application Support\ASL.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreADI.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreADI64.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreAudioToolbox.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreFoundation.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\CoreMedia.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\icudt##.dll" <-- ## = number varies by version
"C:\Program Files\Common Files\Apple\Apple Application Support\libcache.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libdispatch.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libexslt.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libicuin.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libicuuc.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libtidy.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libxml2.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\libxslt.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\lskd.rl"
"C:\Program Files\Common Files\Apple\Apple Application Support\objc.dll"
"C:\Program Files\Common Files\Apple\Apple Application Support\zlib1.dll"
```

## Verify
- Check your OBS log and look for `[CoreAudio encoder]: Adding CoreAudio AAC encoder`
- [File] > [Settings] > [Output] > [Streaming] tab *or* [Recording] tab > [Audio Encoder] > CoreAudio AAC should be available to select.

## Why?
CoreAudio offers better quality AAC streams than ffmpeg AAC. Even the developers of [HandBrake](https://handbrake.fr/docs/en/latest/technical/audio-codecs.html) acknowledge it. This is a superior choice for streaming. However, for recordings you should use ffmpeg Opus if possible. It's even better quality. If you need the AAC for the compatibility, then CoreAudio should be used for recordings as well.

## Status
No updates. Hashes match. Checked 3rd May, 2023.
