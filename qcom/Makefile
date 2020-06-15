# Only include Motorola DTBs
ifeq ($(CONFIG_MMI_DEVICE_DTBS),y)
ifneq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
$(error Moto DT w/o overlay is undefined!!!)
endif

# Motorola Device Trees
dtbo-$(CONFIG_SMITH_DTB) += \
		lito-smith-evt1-overlay.dtbo \
		lito-smith-evt2-overlay.dtbo \
		lito-smith-dvt1a-overlay.dtbo \
                lito-smith-dvt1a2-overlay.dtbo \
		lito-smith-dvt1b-overlay.dtbo \
		lito-smith-dvt1c-overlay.dtbo \
		lito-smith-dvt2-overlay.dtbo \
		lito-smith-pvt-overlay.dtbo

lito-smith-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-dvt1a-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-dvt1a2-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt1b-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt1c-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt2-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-pvt-overlay.dtbo-base := lito-moto-base-v2.dtb

dtbo-$(CONFIG_RACER_DTB) += \
		lito-racer-evt1-overlay.dtbo \
		lito-racer-evt2-overlay.dtbo \
		lito-racer-dvt1-overlay.dtbo

lito-racer-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-racer-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-racer-dvt1-overlay.dtbo-base := lito-moto-base.dtb

dtbo-$(CONFIG_NAIRO_DTB) += \
		lito-nairo-evt1-overlay.dtbo \
		lito-nairo-evt2-overlay.dtbo \
		lito-nairo-evt3-overlay.dtbo \
		lito-nairo-evt3-cap-overlay.dtbo \
		lito-nairo-dvt1-overlay.dtbo \
		lito-nairo-dvt1-cap-overlay.dtbo \
		lito-nairo-dvt1a-overlay.dtbo \
		lito-nairo-dvt1a-cap-overlay.dtbo \
		lito-nairo-dvt2-overlay.dtbo \
		lito-nairo-dvt2-cap-overlay.dtbo \
		lito-nairo-pvt-overlay.dtbo \
		lito-nairo-pvt-cap-overlay.dtbo

lito-nairo-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt3-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt3-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1a-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1a-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt2-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt2-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-pvt-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-pvt-cap-overlay.dtbo-base := lito-moto-base.dtb

dtbo-$(CONFIG_KIEV_DTB) += \
		lagoon-kiev-evt1-overlay.dtbo \
		lagoon-kiev-jp-evt1-overlay.dtbo

lagoon-kiev-evt1-overlay.dtbo-base := lagoon-moto-base.dtb
lagoon-kiev-jp-evt1-overlay.dtbo-base := lagoon-moto-base.dtb

else
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KONA) += \
                kona-cdp-overlay.dtbo \
                kona-cdp-lcd-overlay.dtbo \
                kona-mtp-overlay.dtbo \
                kona-mtp-ws-overlay.dtbo \
                kona-xr-overlay.dtbo \
                kona-rumi-overlay.dtbo \
                kona-qrd-overlay.dtbo \
		kona-xrfusion-overlay.dtbo \
		kona-xrfusion-ult-overlay.dtbo \
                kona-hdk-overlay.dtbo

kona-cdp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-cdp-lcd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-ws-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xr-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-rumi-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-qrd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-ult-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-hdk-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
else
dtb-$(CONFIG_ARCH_KONA) += kona-rumi.dtb \
        kona-mtp.dtb \
        kona-mtp-ws.dtb \
        kona-xr.dtb \
	kona-xrfusion.dtb \
	kona-xrfusion-ult.dtb \
        kona-cdp.dtb \
        kona-cdp-lcd.dtb \
        kona-qrd.dtb \
        kona-v2-rumi.dtb \
        kona-v2-mtp.dtb \
        kona-v2-mtp-ws.dtb \
        kona-v2-cdp.dtb \
        kona-v2-qrd.dtb \
	kona-v2-xrfusion.dtb \
	kona-v2-xrfusion-ult.dtb \
        kona-hdk.dtb \
        kona-v2.1-mtp.dtb \
        kona-v2.1-mtp-ws.dtb \
        kona-v2.1-cdp.dtb \
        kona-v2.1-qrd.dtb \
        kona-v2.1-hdk.dtb \
	kona-v2.1-xrfusion.dtb \
	kona-v2.1-xrfusion-ult.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LITO) += lito-rumi-overlay.dtbo \
                lito-mtp-overlay.dtbo \
                lito-v2-mtp-overlay.dtbo \
                lito-cdp-overlay.dtbo \
                lito-v2-cdp-overlay.dtbo \
                lito-atp-overlay.dtbo \
                lito-v2-atp-overlay.dtbo \
                lito-v2-atp-lcd-overlay.dtbo \
                lito-qrd-overlay.dtbo \
                lito-v2-qrd-overlay.dtbo

lito-rumi-overlay.dtbo-base := lito.dtb lito-v2.dtb
lito-mtp-overlay.dtbo-base := lito.dtb
lito-v2-mtp-overlay.dtbo-base := lito-v2.dtb
lito-cdp-overlay.dtbo-base := lito.dtb
lito-v2-cdp-overlay.dtbo-base := lito-v2.dtb
lito-atp-overlay.dtbo-base := lito.dtb
lito-v2-atp-overlay.dtbo-base := lito-v2.dtb
lito-v2-atp-lcd-overlay.dtbo-base := lito-v2.dtb
lito-qrd-overlay.dtbo-base := lito.dtb
lito-v2-qrd-overlay.dtbo-base := lito-v2.dtb
else
dtb-$(CONFIG_ARCH_LITO) += lito-rumi.dtb \
                lito-mtp.dtb \
                lito-cdp.dtb \
                lito-atp.dtb \
                lito-qrd.dtb \
                lito-v2-mtp.dtb \
                lito-v2-cdp.dtb \
                lito-v2-atp.dtb \
                lito-v2-atp-lcd.dtb \
                lito-v2-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi-overlay.dtbo \
		lagoon-mtp-overlay.dtbo \
		lagoon-mtp-usbc-overlay.dtbo \
		lagoon-cdp-overlay.dtbo \
		lagoon-atp-overlay.dtbo \
		lagoon-qrd-overlay.dtbo

lagoon-rumi-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-usbc-overlay.dtbo-base := lagoon.dtb
lagoon-cdp-overlay.dtbo-base := lagoon.dtb
lagoon-atp-overlay.dtbo-base := lagoon.dtb
lagoon-qrd-overlay.dtbo-base := lagoon.dtb
else
dtb-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi.dtb \
		lagoon-mtp.dtb \
		lagoon-mtp-usbc.dtb \
		lagoon-cdp.dtb \
		lagoon-atp.dtb \
		lagoon-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_BENGAL) += \
                bengal-rumi-overlay.dtbo \
                bengal-qrd-overlay.dtbo \
                bengal-idp-overlay.dtbo \
                bengal-idp-usbc-overlay.dtbo \
                bengalp-idp-overlay.dtbo

bengal-rumi-overlay.dtbo-base := bengal.dtb
bengal-qrd-overlay.dtbo-base := bengal.dtb
bengal-idp-overlay.dtbo-base := bengal.dtb
bengal-idp-usbc-overlay.dtbo-base := bengal.dtb
bengalp-idp-overlay.dtbo-base := bengalp.dtb
else
dtb-$(CONFIG_ARCH_BENGAL) += bengal-rumi.dtb \
                bengal-qrd.dtb \
		bengal-idp.dtb \
		bengal-idp-usbc.dtb \
		bengalp-idp.dtb
endif
endif  # CONFIG_MMI_DEVICE_DTBS

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SCUBA) += \
                scuba-rumi-overlay.dtbo \
                scuba-idp-overlay.dtbo

scuba-rumi-overlay.dtbo-base := scuba.dtb
scuba-idp-overlay.dtbo-base := scuba.dtb
else
dtb-$(CONFIG_ARCH_SCUBA) += scuba-rumi.dtb \
	scuba-idp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
