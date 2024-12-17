# OpenWRT-CI
云编译OpenWRT固件

## 云编译OpenWRT固件，开启内核eBPF，支持DAED 内核级透明代理

官方版：
https://github.com/immortalwrt/immortalwrt.git

高通版：
https://github.com/VIKINGYFY/immortalwrt.git

## 京东云亚瑟 AX1800 Pro DAED 需要更换分区表和uboot,具体使用方法详见恩山帖子: https://www.right.com.cn/forum/thread-8402269-1-1.html

# 12M kernel分区uboot

## https://github.com/bailangvvki/uboot-ipq60xx-build

# 参考

## https://github.com/bailangvvki/VIKINGYFY-OpenWRT-CI

# 固件简要说明：

## 12M kernel alist lucky daed

固件每天早上4点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

MEDIATEK系列、QUALCOMMAX系列、ROCKCHIP系列、X86系列。

# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
