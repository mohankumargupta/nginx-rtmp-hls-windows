# nginx-rtmp-hls-windows

### OBS Studio Configuration
File->Settings -> Stream:
```
Streaming Service: Custom streaming server
Server: rtmp://<Server ip>/live
Stream Key: <Stream key>
```

Example: rtmp://127.0.0.1/live/boo

### Streaming URL

http://&lt;Server ip&gt;/hls/&lt;Stream key&gt;.m3u8


Example: http://127.0.0.1/hls/boo.m3u8
