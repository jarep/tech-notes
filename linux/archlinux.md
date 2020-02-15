
# Useful commands for Arch Linux

## Package management

- Install package:

	`yay -S package`

- Uninstall package

	`yay -R package`

- To update all packages from AUR and official repositories, use -Syu flag.

	`yay -Syu`


## System settings

- Change brigthness:

	`xbacklight -set 50`

- Open audio tool:

	`alsamixer`

## Troubleshooting

- In case of xfce session failure you can try delete the session folder using command below and reboot system

	`rm -r ~/.cache/sessions`

## Mounting USB memory

- You need to create the directory in which you are going to mount the device:

	`mkdir /mnt/usbstick`

- Mount the device as root with this command:

	`mount -U UUID /mnt/usbstick`

	To see which device is your USB device, you can compare the output of `lsblk -f` when the USB device is connected and when it is unconnected.
