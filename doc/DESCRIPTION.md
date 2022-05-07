pith is a lightweight media server that aims to seamlessly integrate your networked media devices. It can act as a standard UPnP media server, but you can also use the built-in web interface to playback media in your browser, or use the same web interface to stream media directly to supported devices and control playback on those devices.

### Features

- UPnP/DLNA support: it acts as both a media server as well as a control device for Media Renderers
- Media Library: set up a media library by scanning your media files. Movies and TV shows are automatically recognized and catalogued. Metadata is fetched from TMDb and/or locally found kodi-style .nfo files.
- Sonarr and CouchPotato integration: directly browse your Sonarr or CouchPotato libraries without having to set up scanning. Quick and efficient.
- Least-effort live-transcoding (experimental): playback your media files in the browser without worrying about codecs. pith will live-transcode your files for your browser automatically, and tries to do as little as possible while doing so to keep the load on your server low, as well as hardware requirements.
- Works great with Kodi; the UPnP media server works great for Kodi. It exposes the same metadata Kodi uses internally, so it's just like having the media locally on your Kodi box. Playback state is shared between all devices; so if you stop playing on one device, you can easily resume playback on another from the same point in time.
