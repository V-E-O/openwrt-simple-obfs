Simple-obfs for OpenWrt
===

编译
---

 - 从 OpenWrt 的 [SDK][S] 编译

   ```bash
   # 以 ar71xx 平台为例
   tar xjf OpenWrt-SDK-ar71xx-for-linux-x86_64-gcc-4.8-linaro_uClibc-0.9.33.2.tar.bz2
   cd OpenWrt-SDK-ar71xx-*
   # 获取 simple-obfs Makefile
   git clone https://github.com/V-E-O/openwrt-simple-obfs.git package/simple-obfs
   # 开始编译
   make package/simple-obfs/compile V=s
   ```


  [S]: https://wiki.openwrt.org/doc/howto/obtain.firmware.sdk
