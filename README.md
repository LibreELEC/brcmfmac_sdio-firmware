# brcmfmac_sdio-firmware
The following wireless/bluetooth modules are currently supported:

* AP6212 Khadas_VIM _basic_, NanoPi K2
* AP6255 WeTek_Hub v2, Khadas_VIM _pro_
* AP6330 WeTek_Play_2, Cubox-i2/4
* AP6335 WeTek_Hub v1

Use of `hciattach` and `brcm_patchram_plus` are discouraged as firmware loading can be triggered by including `compatible = "brcm,bcm43438-bt";` nodes in device-tree. For more information refer to [Linux Kernel Documentation](https://github.com/torvalds/linux/blob/master/Documentation/devicetree/bindings/net/broadcom-bluetooth.txt).

