# Copyright (C) 2020 Silvan
include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for UnblockNeteaseMusic Go
LUCI_DEPENDS:=+bash +coreutils-nohup +curl +dnsmasq-full +ipset +UnblockNeteaseMusic-Go
LUCI_PKGARCH:=all
PKG_NAME:=luci-app-unblockneteasemusic-go
PKG_VERSION:=1.4
PKG_RELEASE:=1

PKG_MAINTAINER:=https://github.com/cnsilvan/luci-app-unblockneteasemusic

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
