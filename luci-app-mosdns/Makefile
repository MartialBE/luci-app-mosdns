include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-mosdns
PKG_VERSION:=2.1.1
PKG_RELEASE:=2

LUCI_TITLE:=LuCI Support for mosdns
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+mosdns +jsonfilter +luci-compat +curl

define Package/$(PKG_NAME)/conffiles
/etc/config/mosdns
/etc/mosdns/config_custom.yaml
/etc/mosdns/rule
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
