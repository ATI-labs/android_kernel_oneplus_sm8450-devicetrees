
dtbo-$(CONFIG_ARCH_WAIPIO) += waipio-audio.dtbo \
                 waipio-audio-cdp.dtbo \
                 waipio-audio-mtp.dtbo \
                 waipio-audio-qrd.dtbo \
                 waipio-audio-atp.dtbo \
                 waipio-audio-rumi.dtbo \
                 waipio-audio-hdk.dtbo

dtbo-$(CONFIG_ARCH_DIWALI) += diwali-audio.dtbo \
                 diwali-audio-idp.dtbo \
                 diwali-audio-qrd.dtbo \
                 diwali-audio-idp-usbc.dtbo

dtbo-$(CONFIG_ARCH_CAPE) += cape-audio.dtbo \
                 cape-audio-cdp.dtbo \
                 cape-audio-mtp.dtbo \
                 cape-audio-atp.dtbo

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
