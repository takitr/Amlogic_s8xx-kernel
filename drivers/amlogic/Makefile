##########################################
########## Amlogic Drivers ###############
##########################################

##########################################
## The order of directories matter.
## Do not change.
##########################################


obj-y +=early_init/
###For Display, this is for quick logo show##
obj-$(CONFIG_AM_DISPLAY_MODULE) += display/

obj-$(CONFIG_POST_PROCESS_MANAGER) += ppmgr/

obj-$(CONFIG_V4L_AMLOGIC_VIDEO) += video_dev/
obj-$(CONFIG_V4L_AMLOGIC_VIDEO2) += video_dev/
obj-$(CONFIG_AMLOGIC_IONVIDEO) += ionvideo/

obj-$(CONFIG_DEINTERLACE) += deinterlace/

##### Basic drivers#####

obj-y += watchdog/
obj-y += secure/
obj-y += securitykeys/
obj-y += keymanage/

obj-y += uart/
obj-y += of/
obj-y += usb/
obj-y += cpufreq/
obj-$(CONFIG_GPIO_AMLOGIC) += gpio/
obj-y += pinctrl/

obj-$(CONFIG_AML_NEXT_GEN_NAND) += nand/amlnf/
obj-$(CONFIG_AM_NAND) += nand/nand/

obj-y += ethernet/

obj-$(CONFIG_AM_CANVAS) += canvas/

obj-y += amports/

# ve&cm
obj-y += amvecm/

obj-$(CONFIG_I2C) += i2c/

#obj-y += extern_io/

obj-$(CONFIG_EFUSE)+=efuse/
obj-$(CONFIG_AM_INPUT)		+= input/

obj-$(CONFIG_AML_TOUCH_ALGORITHM_SUPPORT) += touch/

obj-$(CONFIG_AMLOGIC_SPI_NOR) += spi_nor/

#obj-$(CONFIG_CARDREADER) += cardreader/
obj-$(CONFIG_MMC_AML) +=mmc/

obj-$(CONFIG_AML_VFM) += vfm/

obj-$(CONFIG_AML_AUDIO_DSP) += audiodsp/

obj-$(CONFIG_AML_RTC)+= rtc/

obj-y += power/

obj-$(CONFIG_AML_PMU_ALGORITHM_SUPPORT) += pmu/

obj-y += tvin_v4l2/
obj-$(CONFIG_TVIN) += tvin/

obj-$(CONFIG_AML_EXT_HDMIIN) += ext_hdmiin/

obj-y += thermal/


#####Sound system is later init in kernel default..######################
obj-$(CONFIG_AMAUDIO) += amaudio/
obj-$(CONFIG_AMAUDIO2) += amaudio2/
obj-y += mhl/
obj-y += hdmi/

obj-$(CONFIG_AM_DVB) += dvb_tv/
obj-$(CONFIG_AM_SMARTCARD) += smartcard/

obj-$(CONFIG_AM_WIFI) += wifi/

obj-y += bluetooth/
obj-$(CONFIG_MESON_NFC) += nfc/

obj-$(CONFIG_VIDEO_AMLOGIC_CAPTURE) += camera/

obj-$(CONFIG_AMLOGIC_MIPI) += mipi/

obj-$(CONFIG_D2D3_PROCESS) += d2d3/

obj-$(CONFIG_AML_REG_DEBUG) += regd/

obj-$(CONFIG_AML_WATCHDOG) += watchdog/

obj-$(CONFIG_UMP) += gpu/ump/
obj-$(CONFIG_MALI400) += gpu/mali/

obj-$(CONFIG_AMLOGIC_ION) += ion_dev/

obj-y += instaboot/

obj-y += crypto/

#obj-$(CONFIG_MESON_TRUSTZONE) += trustzone/
obj-$(CONFIG_MESON_TRUSTZONE) += secure_monitor/
obj-y += spi/

obj-y += defendkey/

obj-$(CONFIG_VFD) += vfd/
