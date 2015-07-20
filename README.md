# nodebots_MeWIFI

This is a slightly tweaked version of the amazing work by [makebot](http://www.makeblock.cc/) team who built an ESP8266 wifi based UDP <-> serial bridge.

# Building

Update your projects WORKDIR path in the `Dockerfile`.

Then build the project.

```
docker build -t esp8266-build-bridge .
docker run -v /Users:/Users -t esp8266-build-bridge make
```

# flashing

```
make flash
```

# License

Most of the sources to this came from http://git.oschina.net/riven/MeWifi-Module

My code is Copyright (c) 2014 Mark Wolfe and licensed under the MIT license.
