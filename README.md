# My Unraid Templates
1. emby_unLockd 4.6.7
edit: /boot/config/go
modprobe i915
chown nobody:users /dev/dri
chmod 0777 /dev/dri/*
2.clouddrive.xml
edit: /boot/config/go
mount --make-shared /mnt/disk1/
