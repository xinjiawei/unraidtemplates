# My Unraid Templates
> 目前unraid模板有个好处是之后可以一键更新版本.
## 用法
> 6.10.* 以上版本重新开启模板, 方法来源于 https://github.com/shuosiw/unraid 改进了一些
### Unraid 6.10.x 以上版本

Unraid 6.10 版本开始已经去掉模版仓库功能，详见：[UNRAID OS VERSION 6.10.0-RC1 AVAILABLE](https://forums.unraid.net/bug-reports/prereleases/unraid-os-version-6100-rc1-available-r1514/?tab=comments#comment-15110)

> If you're one of the (very rare) users who still leverages the Template Repositories section, this has been entirely removed

针对 6.10.x 版本，可通过以下方式使用：

1. 打开 Unraid 终端，执行以下命令：

    ```
    mkdir -p /boot/config/plugins/dockerMan/templates;
    cd /boot/config/plugins/dockerMan/templates;
    wget -qO- https://github.com/xinjiawei/unraidtemplates/releases/download/1.0.0/unraidtemplates-master.tgz | tar -zxf - ;
    ```

2. 刷新 Unraid 管理后台浏览器页面（比如 Windows 按 F5 刷新）
3. 参考下方**添加容器**来使用，导入的模版会存在于 `Default templates` 分类中


### unraid 6.9.x 及以下版本添加模板库

打开 unraid 的 docker 页面：

1. 将本仓库地址 https://github.com/xinjiawei/unraidtemplates 填入 **Template repositories**
2. 点击 **SAVE** 保存，unraid 会自动拉取模板库并刷新页面

### 添加容器

在 Unraid 自动刷新页面之后，点击 **ADD CONTAINER** 添加容器

## 介绍
### emby_unLockd
详情见博客

### nastool
请修改为自己的下载器下载目录和仓库目录

### ossrs.xml
ossrs需要外挂配置文件,请从ossrs官网下载并挂载


### webdav-apache.xml
webdav服务器,默认挂载/mnt/user目录

### iperf3-server
区域网测速服务器. 详情客户端配置请百度, 安卓可以使用TPLINK旗下的网络百宝箱.
