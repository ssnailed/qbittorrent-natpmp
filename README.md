# qBittorrent-natpmp
I forked the [original repo](https://github.com/soxfor/qbittorrent-natmap) to make it compatible with the [linuxserver/docker-wireguard](https://github.com/linuxserver/docker-wireguard) container.

## Not using gluetun
Since I only use wireguard (a silent protocol) forced health checks on the wireguard container are pointless. On top of this I've had problems with the firewalling done by the gluetun container. Rather than troubleshooting that I just deleted a bunch of code from soxfor's container to make it compatible with my preferred vpn container.
