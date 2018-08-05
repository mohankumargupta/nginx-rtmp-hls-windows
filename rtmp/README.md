# Create an RTMP endpoint with nginx
The nginx.conf in this directory allows for:
- Push RTMP stream from Xsplit/ObStudio to NGINX  RTMP URL: http://<IP OF NGINX SERVER>/live/<stream key> 
     * Stream key may be in a separate field, so then RTMP URL will be eg. http://127.0.0.1/live
- Play stream in VLC->Media->network stream http://<IP OF NGINX SERVER>/live/<stream key>
    * Don't use localhost, use 127.0.0.1 instead
