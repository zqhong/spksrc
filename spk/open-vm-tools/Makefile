SPK_NAME = open-vm-tools
SPK_VERS = 11.3.5
SPK_REV = 1
SPK_ICON = src/open-vm-tools.png
BETA = 1

DEPENDS = cross/$(SPK_NAME)

MAINTAINER = perrin-1
DESCRIPTION = open-vm-tools is a set of services and modules that enable several features in VMware products for better management of, and seamless user interactions with, guests.
RELOAD_UI = yes
DISPLAY_NAME = VMware Tools
CHANGELOG = "SPK Open-vm-tools | 23 SEP 2021 | Build 18557794"

HOMEPAGE = https://github.com/vmware/open-vm-tools
LICENSE  = GPLv2/LGPLv2.1

# 'auto' reserved value grabs SPK_NAME
SERVICE_USER  = auto
SERVICE_SETUP = src/service-setup.sh
CONF_DIR      = src/conf
STARTABLE     = yes

include ../../mk/spksrc.spk.mk
