# I use Arch BTW
  ![neofetch](./neofetch.png)
# Hardware Requirements
  - An OTG mini USB to USB adapter
  - A USB flash drive with at least 1 GB of storage
  - A TI-Nspire CX II (CX II CAS or CX-T is fine but not CX)
# Helpful Links
Disable network: https://www.reddit.com/r/archlinux/comments/4a3abs/switch_systemdnetworkd_to_network_manager/ 
`systemctl disable systemd-networkd.service; systemctl disable systemd-resolved.service`
https://www.reddit.com/r/archlinux/comments/pupbkh/failed_to_start_network_configuration_on_custom/

Kernel Source: https://github.com/Vogtinator/linux/tree/cxII-usb-host

Tutorial: https://www.omnimaga.org/ti-calculator-programming-and-support/linux-on-ti-nspire-cx-ii-!/

Setup commands: `sudo cp /usr/bin/qemu-arm-static /mnt/usr/bin` `sudo bsdtar xzvf ArchLinuxARM-armv5-latest.tar.gz -C /mnt`

https://askubuntu.com/questions/644010/ubuntu-cant-read-my-usb-device-descriptor-read-64-error-110

Package Manager for ARMv5te soft: https://github.com/Optware/Optware-ng
