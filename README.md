# nginx-rtmp-hls-windows

### OBS Studio Configuration
File->Settings -> Stream:
```
Streaming Service: Custom streaming server
Server: rtmp://<Server ip>/live
Stream Key: <Stream key>
```

Example: rtmp://localhost/live/boo

### Streaming URL

http://&lt;Server ip&gt;/hls/&lt;Stream key&gt;.m3u8


Example: http://localhost/hls/boo.m3u8
