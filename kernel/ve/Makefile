#
# kernel/ve/Makefile
#
# Copyright (c) 2000-2015 Parallels IP Holdings GmbH
#

obj-$(CONFIG_VE) = ve.o veowner.o hooks.o vzstat_core.o ve-kobject.o
obj-$(CONFIG_VZ_WDOG) += vzwdog.o
obj-$(CONFIG_VE_CALLS) += vzmon.o

vzmon-objs = vecalls.o

obj-$(CONFIG_VZ_DEV) += vzdev.o
obj-$(CONFIG_VZ_EVENT) += vzevent.o

obj-$(CONFIG_VE_NETDEV_ACCOUNTING) += vznetstat/vznetstat.o vznetstat/ip_vznetstat.o vznetstat/ip6_vznetstat.o

obj-$(CONFIG_VZ_LIST) += vzlist.o
obj-$(CONFIG_VE_CALLS) += vzstat.o

obj-$(CONFIG_VZ_IOLIMIT) += vziolimit.o

obj-$(CONFIG_VE_IPTABLES) += ve.o

obj-m += dummy/ip6_vzprivnet.o
obj-m += dummy/ip_vzprivnet.o
obj-m += dummy/pio_nfs.o
