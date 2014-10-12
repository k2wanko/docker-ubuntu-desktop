# Ubuntu Desktop

# Usage

```
docker run -it --rm -p 5901:5901 k2wanko/ubuntu-desktop
USER=root vncserver :1 -geometry 1280x800 -depth 24
```

Connect to `vnc://<host>:5901`

[VNC® Viewer for Google Chrome™](https://chrome.google.com/webstore/detail/vnc%C2%AE-viewer-for-google-ch/iabmpiboiopbgfabjmgeedhcmjenhbla) is my favorite soft.
