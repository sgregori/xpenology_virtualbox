# xpenology_virtualbox
Some cheats for Xpenology on Virtualbox


# Using Serial Console on Virtualbox:
![image](https://user-images.githubusercontent.com/8670186/147818713-c232cfc8-d714-48a9-8a2d-6a9ccc5a8b26.png)
```
socat UNIX-CONNECT:/tmp/ds3615 PTY,link=/tmp/ds3615-pty &
screen /tmp/ds3615-pty
```
