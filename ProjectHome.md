![http://rhobuntu.googlecode.com/files/Project_logo.png](http://rhobuntu.googlecode.com/files/Project_logo.png)

Our goal is to create a user-friendly Ubuntu-like Distribution (ARM architecture) codenamed **Rhobuntu** which runs on HTC Touch Pro 2 (Rhodium). Rhodium is a Windows (C) Mobile smartphone with a powerful 528MHz ARM CPU, 288MB RAM, WVGA touchscreen, WiFi, 3G, GPS and Bluetooth. We can reuse many items from the Rhodium Android Port like kernel, modules and some tools.

So far we can boot Ubuntu from WinMo using HaRet. Touchscreen, keyboard, WiFi and 3G partially work. You can also install Apps via Synaptics. In this stage Rhobuntu is already quite usable.

[Check out the photos ](http://picasaweb.google.com/113730655276627977919/RhobuntuUbuntuOnRhodium#)

# Legal Information #

Rhobuntu basically consists of three parts, namely the kernel, the original rootfs and tweaks to the original rootfs.

The kernel comes from this repository
http://gitorious.org/linux-on-qualcomm-s-msm/linux-msm . You can download it already compiled from here http://glemsom.anapnea.net/android/htc-msm-android/#
For more information please visit http://htc-linux.org/wiki

The original rootfs originates from the [Ubuntu ARM Port Project](https://wiki.ubuntu.com/ARM). Ubuntu developers provide a tool called [rootstock](https://wiki.ubuntu.com/ARM/RootfsFromScratch) which allows everybody to create a preconfigured rootfs. That's how we created a rootfs for Rhobuntu.

**Neither the kernel nor the original rootfs are in any way related to the Rhobuntu project. We only use them according to the terms of the GPL license.**

The main task of the Rhobuntu developers is combining the kernel and the rootfs in a way that it can become a proper linux distro for the supported HTC devices. To achieve that we mostly modify the rootfs, by adding/removing/tweaking drivers, apps or
services.

# We are very thankful to the followings projects #

  * Rhodium Android Port
  * Handhelds Mojo
  * Zubuntu
  * UBUNTU 8.04 for Xperia X1

and to the following people

  * phhusson
  * fatsal

for their help, infos, support or code