docker-ubuntu-vnc-desktop
=========================

Build yourself
```
docker build --rm -t argouml/ubuntu-desktop-lxde-vnc docker-ubuntu-vnc-desktop
```

Run
```
docker run -i -t -p 6080:6080 argouml/ubuntu-desktop-lxde-vnc
```

Browse http://127.0.0.1:6080/vnc.html

<img src="https://raw.github.com/fcwu/docker-ubuntu-vnc-desktop/master/screenshots/lxde.png" width=400/>


Trobleshooting
==================

1. boot2docker connection issue, https://github.com/fcwu/docker-ubuntu-vnc-desktop/issues/2


License
==================

desktop-mirror is under the Apache 2.0 license. See the LICENSE file for details.
