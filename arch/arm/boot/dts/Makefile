ifeq ($(CONFIG_OF),y)

dtb-$(CONFIG_ARCH_VERSATILE) += versatile-ab.dtb \
	versatile-pb.dtb
dtb-$(CONFIG_ARCH_ZYNQ) += zynq-zc702.dtb
dtb-$(CONFIG_ARCH_MESON8) += meson8_skt.dtb \
	meson8m2_skt.dtb

DTB_NAMES := $(subst $\",,$(CONFIG_BUILD_ARM_APPENDED_DTB_IMAGE_NAMES))
ifneq ($(DTB_NAMES),)
DTB_LIST := $(addsuffix .dtb,$(DTB_NAMES))
else
DTB_LIST := $(dtb-y)
endif

targets += dtbs
targets += $(DTB_LIST)
endif

# *.dtb used to be generated in the directory above. Clean out the
# old build results so people don't accidentally use them.
dtbs: $(addprefix $(obj)/, $(DTB_LIST))
	$(Q)rm -f $(obj)/../*.dtb

#clean-files := *.dtb
