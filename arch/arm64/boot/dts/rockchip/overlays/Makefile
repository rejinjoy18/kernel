# Overlays for the ROCK Pi platform

dtbo-$(CONFIG_ARCH_ROCKCHIP) += \
	console-on-uart4.dtbo \
	console-disabled.dtbo \
	two-color-led.dtbo \
	at24c02.dtbo

targets += dtbs dtbs_install
targets += $(dtbo-y)

always		:= $(dtbo-y)
clean-files	:= *.dtbo
