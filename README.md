# CoreAudio
CoreAudio stand-alone for Windows. Make it easier to use for OBS.

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

Check your OBS log and look for `[CoreAudio encoder]: Adding CoreAudio AAC encoder`
