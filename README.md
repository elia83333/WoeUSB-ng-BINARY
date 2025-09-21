<div align="center">
<h1>WoeUSB-ng-Binary</h1>
<img src=".github/woeusb-logo.png" alt="brand" width="28%" />
</div>

_A Linux program to create a Windows USB stick installer from a real Windows DVD or image._

This package contains one programs:

* **woeusb**: A command-line utility that enables you to create your own bootable Windows installation USB storage device from an existing Windows Installation disc or disk image

# woeusb-GUI

Currently this project doesn't support woeusb-GUI, PYInstaller just doesnt work with it somehow...

# Installation

Download the dependencies

#### Ubuntu

```shell
sudo apt install git p7zip-full python3-pip python3-wxgtk4.0 grub2-common grub-pc-bin parted dosfstools ntfs-3g
```

#### Fedora (tested on: Fedora Workstation 33)
```shell
sudo dnf install git p7zip p7zip-plugins python3-pip python3-wxpython4
```

Download the binary from https://github.com/elia83333/WoeUSB-ng-BINARY/releases/tag/binary

```shell
wget https://github.com/elia83333/WoeUSB-ng-BINARY/releases/tag/binary
```

Run it

```shell
sudo ./WoeUSB-Binary
```

# How do i know it's safe?

Well im pretty known in ATL community, you can do a malware analysis on it if you'd like, if you do open a issue with it and i'll include it here
or you can just trust me and save urself the hassle of pip and python stuff.
VirusTotal says it's 100% safe btw

## License
WoeUSB-ng is distributed under the [GPL license](https://github.com/WoeUSB/WoeUSB-ng/blob/master/COPYING).

ALL CREDITS TO WoeUSB-ng!
I ONLY BUNDLED THE EXECUTABLE
