# easyconnect_archlinux
基于deb版本安装的的深信服vpn客户端，适用于Archlinux。

参考[aur easyconnect](https://aur.archlinux.org/packages/easyconnect/)修改。
# ONE 安装

1. 克隆本仓库
```
clone https://github.com/jialeens/easyconnect_archlinux.git
```
2. 替换`PKGBUILD`中的easyconnect软件URL为自己公司的vpn服务器指向的deb安装包。
3. 使用md5sum命令重新计算文件包校验合，也可以配置为忽略检查。
4. 执行`makepkg install`进行安装。

# TWO 已知问题

- 使用网页登录，浏览器无法打开客户端
    - 直接打开easyconnect应用程序。
- 登录后，弹出的网页一直加载
    - 可以先测试一下此时是否已经连接上vpn，如果已经连上，可以不用管。
