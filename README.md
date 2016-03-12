# zfs-utils
zfs utilities in docker container

Based off of debian image and then following instructions on:
http://zfsonlinux.org/debian.html

Does not actively run any processes, should only be used to run zfs commands. Also requires use of /dev/zfs.

Example run command:
docker run --rm --device /dev/zfs:/dev/zfs:rw crazymanjinn/zfs-utils zpool status
