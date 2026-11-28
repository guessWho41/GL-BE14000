# GL-BE14000
GL.iNet Flint 4 (GL-BE14000) custom build with LuCi.
Repository for building custom [OpenWrt](https://github.com/openwrt/openwrt) for GL.iNet Flint 4 (GL-BE14000) based on [Cjom's](https://forum.openwrt.org/u/cjom) [GL-MT6000 custom OpenWrt firmware builder](https://github.com/cjom/gl-mt6000) with following customizations:

<!-- package-list-start -->
- [Pesa1234's](https://forum.openwrt.org/u/pesa1234) [patches](https://github.com/pesa1234/openwrt)
- Dropbear replaced with OpenSSH and SFTP with [hardened config](https://github.com/cjom/GL-MT6000/tree/main/files/etc/ssh) by [Cjom](https://forum.openwrt.org/u/cjom)
- Mbed TLS relaced with OpenSSL
- Wi-Fi UCODE scripts
- AdBlock-Fast
- Bridger
- Dynamic DNS Client
- dnsproxy with [luci-app-dnsproxy](https://github.com/muink/luci-app-dnsproxy) by [muink](https://github.com/muink)
- Irqbalance
- mwan3 [nftables port](https://github.com/dl12345/mwan3) by [dl12345](https://forum.openwrt.org/u/dl12345)
- qosify
- TCP BBR
- MiniUPnPd
- usteer [next generation](https://github.com/NilsRo/usteer-ng) by [NilsRo](https://forum.openwrt.org/u/nilsro/)
- Wireguard
- ZRAM
- Removed: odhcpd and ppp
<!-- package-list-end -->
