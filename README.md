#### small-package

*  常用OpenWrt软件包源码合集，同步上游更新！

*  关于有好的插件请在issues提交

*  感谢以上github仓库所有者！

#### 使用方式：

```bash
 sed -i '$a src-git smpackage https://github.com/lllrrr2/small-package' feeds.conf.default
```
对于强迫症的同学（有报错信息、或Lean源码编译出错的情况），请尝试删除冲突的插件

```bash
rm -rf feeds/smpackage/{base-files,dnsmasq,firewall*,fullconenat,libnftnl,nftables,ppp,opkg,ucl,upx,vsftpd*,miniupnpd-iptables,wireless-regdb}
```











