# My Unraid Templates

## emby_unLockd 4.6.7
### Unraid 使用前请编辑: /boot/config/go ,增加
> modprobe i915
<br>chown nobody:users /dev/dri
<br>chmod 0777 /dev/dri/*
<br>
to mount the graphics card<br>
来挂载显卡<br>
<br>
in addition, you need to make following changes to suit your env<br>
除此之外,你还需要根据自己的情况更改<br>
<br>
<b>UID</b><br>
<b>GID</b><br>
<b>GIDLIST</b><br>
<br>
to adapt y system and get graphics card access <br>
来适配你的系统,获取显卡权限<br>
<br>
you can get the parameters, using commamd:id 你可以用id命令获取这些参数<br>
遇到问题请进群<br>

## clouddrive.xml
### 编辑: /boot/config/go
> mount --make-shared /mnt/disk1/
