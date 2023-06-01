# Distro-Splash
Distro Splash is a Plymouth Theme that shows the Distro's Logo and the Linux Logo Watermark underneath the boot splash.


# Preview
![1](preview.png)

# Installation
Clone this repository:
1. ``git clone https://github.com/RuahWonders/Distro-Splash``
Or Alternatively, download the boot splash theme of your distro from the repository's [releases](https://github.com/RuahWonders/Distro-Splash) page.
2. Copy the Distro Splash repository folder to ``/usr/share/plymouth/themes``
3. Set the Default Theme to the Distro Splash theme
- For Ubuntu:
type ``sudo update-alternatives --config default.plymouth and select the Distro-Splash Theme``
- Other Distros:
type ``sudo plymouth--set-default-theme`` and type the Distro-Splash name.
