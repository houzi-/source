# Copyright (c) 2013 The Linux Foundation. All rights reserved.
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=ipq806x
BOARDNAME:=Qualcomm Atheros IPQ806X
FEATURES:=squashfs nand ubifs fpu
CPU_TYPE:=cortex-a9
CPU_SUBTYPE:=neon-vfpv4
MAINTAINER:=John Crispin <john@phrozen.org>

KERNEL_PATCHVER:=3.18

KERNELNAME:=zImage Image dtbs

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	kmod-leds-gpio kmod-gpio-button-hotplug swconfig \
	kmod-ata-core kmod-ata-ahci kmod-ata-ahci-platform


$(eval $(call BuildTarget))
