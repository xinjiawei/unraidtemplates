# My Unraid Templates

## emby_unLockd
### Unraid 使用前请编辑: /boot/config/go ,增加
> modprobe i915
<br>chown nobody:users /dev/dri
<br>chmod 0777 /dev/dri/*
<br>
来挂载显卡<br>
<br>
除此之外,你还需要根据自己的情况更改<br>
<br>
<b>UID</b><br>
<b>GID</b><br>
<b>GIDLIST</b><br>
<br>
来适配你的系统,获取显卡权限<br>
<br>
你可以用id命令获取这些参数<br>

## ossrs.xml
ossrs需要外挂配置文件,请从ossrs官网下载并挂载


## webdav-apache.xml
webdav服务器,默认挂载/mnt/user目录

## iperf3-server
区域网测速服务器. 详情客户端配置请百度, 安卓可以使用TPLINK旗下的网络百宝箱.
