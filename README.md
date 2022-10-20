# Actions-Openwrt编译

**Openwrt项目**>[coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

**Openwrt扩展插件项目**>[kenzok8/openwrt-packages](https://github.com/kenzok8/openwrt-packages)

**编译Openwrt项目**>[esirplayground/AutoBuild-OpenWrt](https://github.com/esirplayground/AutoBuild-OpenWrt)

🎉🎉🎉**感谢**🎉🎉🎉

## 日常命令

#### 获取更新

`./scripts/feeds update -a`

#### 安装更新

`./scripts/feeds install -a`

#### 设置菜单

`make menuconfig`

#### 获取.config配置

`./scripts/diffconfig.sh > ./diffconfig`

#### 设置socks5代理

`export ALL_PROXY=socks5://127.0.0.1:7890`