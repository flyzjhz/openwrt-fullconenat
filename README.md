# Netfilter and iptables extension for [FULLCONENAT](https://github.com/Chion82/netfilter-full-cone-nat) target.

Compile
```
# cd to OpenWrt source path
# Clone this repo
git clone -b master --single-branch https://github.com/LGA1150/openwrt-fullconenat package/fullconenat
# Select Network -> Firewall -> iptables-mod-fullconenat
make menuconfig
# Compile
make V=s
```
