#
# Makefile for the DVB driver.
#

obj-$(CONFIG_AM_DVB) += aml.o

aml-objs=aml_dvb.o aml_dmx.o

obj-$(CONFIG_AM_DVB) += aml_fe.o

obj-$(CONFIG_AM_CI) += amlci/

obj-$(CONFIG_AM_M6_DEMOD) += amldemod/

ifneq ($(wildcard $(srctree)/drivers/amlogic/hardware/dvb),)
	obj-$(CONFIG_AM_ATBM8869) += drivers/amlogic/hardware/dvb/altobeam/drivers/atbm887x/
	obj-$(CONFIG_AM_SI2177)   += drivers/amlogic/hardware/dvb/silabs/drivers/si2177/
	obj-$(CONFIG_AM_AVL6211)  += drivers/amlogic/hardware/dvb/availink/drivers/avl6211/
	obj-$(CONFIG_AM_SI2168)   += drivers/amlogic/hardware/dvb/silabs/drivers/si2168/
	obj-$(CONFIG_AM_MXL101) += drivers/amlogic/hardware/dvb/maxlinear/drivers/mxl101/
endif

EXTRA_CFLAGS += -I.
