## GPIO IRQ userspace support for OpenWRT/LEDE

OpenWRT/LEDE kernel module to provide userspace support for GPIO interrupts.

**Note**: needs kernel support for GPIO interrupts. Most platforms in current LEDE/OpenWrt nowadays (2017) have that. For older ath79 kernels, [there is a patch](https://github.com/GBert/openwrt-misc/tree/master/gpio-test/src/patches-3.14) which adds this support.
