# VX Linux
A continuation/culmination of DXT2 and Xevuan with a focus on making initial setup as quick and simple as double-clicking a few helper scripts. This is the core version and only features an archiver, file manager, partition manager and text editor. The pro version will feature a software set decided by its users.

**New Features**
- Automatic driver installation & configuration for Bluetooth, Intel graphics & SSD hardware
- Hot corners (/usr/share/VX/hot-corners/hot-corners.conf)

**Improved Features**
- Service listing

**Modules**
- Drivers: 
alsa-extras amd-gfx brother-printers hp-printers nvidia-latest nvidia-legacy nvidia-nouveau

- Software: 
brave chrome flatpak-runtimes freeoffice nodejs nodejs-lts onlyoffice openoffice opera steam sublime ungoogled-chromium virtualbox visual-studio-code vivaldi

- Utility: 
active-hosts backup-os ipv4-keepalive local-rtc monitor-interface public-ip purge-old-kernels remove-unused-packages scaling-performance scaling-powersave services updatetz

**Notes**
- If troubleshooting a machine you will need to disable quiet boot to see error messages. Open a terminal and run<br><code>sudo quietboot-off</code> and reboot.
- Sudo password is disabled. To revert to default sudo behaviour open a terminal and run<br><code>sudo password-on</code>
- Fine-tune your system quickly with other handy on/off shortcuts:<br><code>autologin-on</code> <code>grub-off</code> <code>osprober-on</code> <code>ssh-on</code>
