# (C) Copyright 2014-2015 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y  := mx6sxsabresd.o

extra-$(CONFIG_USE_PLUGIN) :=  plugin.bin
$(obj)/plugin.bin: $(obj)/plugin.o
	$(OBJCOPY) -O binary --gap-fill 0xff $< $@
