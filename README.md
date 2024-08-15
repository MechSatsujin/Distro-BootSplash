# Update
May work for a new version, idk 

# Distro-Splash
Distro Splash is a Plymouth Theme that shows the Distro's Logo and the Linux Logo Watermark underneath the boot splash. It uses the two-step module.


# Preview
![1](preview.png)

# Installation

1. Download the boot splash theme of your distro from the repository's [releases](https://github.com/RuahWonders/Distro-Splash) page.

2. Copy the Distro Splash repository folder to ``/usr/share/plymouth/themes``

3. Set the Default Theme to the Distro Splash theme 
- For Ubuntu and Ubuntu-based:
   - Replace the brackets with your distro of choice
   1. Install the plymouth theme : ``sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/Distro-Splash-[Ubuntu|Fedora|Arch|LinuxMint]/Distro-Splash-[Ubuntu|Fedora|Arch|LinuxMint].plymouth 100,``
   2.  ``sudo update-alternatives --config default.plymouth`` and select the Distro-Splash Theme
- Debian, Arch, Fedora and other distros: type ``sudo plymouth--set-default-theme -R Distro-Splash-[Ubuntu|Fedora|Arch|LinuxMint]``
