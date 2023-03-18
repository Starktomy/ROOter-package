#Owned by DairyMan@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-rooter16
PKG_VERSION:=1.000
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-rooter16
  SECTION:=utils
  CATEGORY:=ROOter
  DEPENDS:=+luci +ext-rooter-basic \
		+luci-app-mwan3 \
		+luci-app-ddns +ddns-scripts \
		+bwmon +464xlat +luci-app-ttyd \
		+ca-bundle +ca-certificates +libustream-wolfssl \
		+luci-app-sqm +kmod-sched-cake \
		+ext-command  \
		+ext-extra +luci-app-wol \
		+qlog +luci-ssl +usbutils +openssl-util +irqbalance +ext-splashconfig \
		+nano +picocom +wpad +wget +qfirehose
  TITLE:=ROOter support for 16meg and larger routers
  PKGARCH:=all
endef

define Package/ext-rooter16/description
  Helper scripts to enable ROOter on 16meg and larger routers
endef


define Build/Compile
endef

$(eval $(call BuildPackage,ext-rooter16))
