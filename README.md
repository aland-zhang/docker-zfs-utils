# zfs-utils
zfs utilities in docker container

----

Based off of debian image and then following instructions on:
http://zfsonlinux.org/debian.html

Does not actively run any processes, only starts an interactive shell. Also requires use of /dev/zfs.

General-use run command:
docker run --rm -it --device /dev/zfs crazymanjinn/zfs-utils
