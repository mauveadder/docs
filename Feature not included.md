# Please use this exact paragraph (formatting and links) at the beginning of an article for a feature that is not included in precompiled builds

!> **This feature is not included in precompiled binaries.**     
To use it you must [compile your build](compile-your-build). Add the following to `user_config_override.h`:
```
#ifndef USE_SHUTTER
#define USE_SHUTTER           // Add Shutter support (+6k code)
#endif
```
----