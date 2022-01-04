### My Unraid Templates

## emby_unLockd 4.6.7
# edit: /boot/config/go
> modprobe i915
<br>chown nobody:users /dev/dri
<br>chmod 0777 /dev/dri/*
## clouddrive.xml
# edit: /boot/config/go
> mount --make-shared /mnt/disk1/
