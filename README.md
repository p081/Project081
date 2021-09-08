# Project 081
<img width="256" alt="Project081" src="https://user-images.githubusercontent.com/71722170/124338538-d20d2e80-dba8-11eb-813a-846e37cfd656.png">

Running Mac OS X 10.4 Tiger on Early 2008 [Penryn] Macs

### Quick Links
Documentation: Will be released with Beta 2

Written Guide: Will be released with Beta 2

Compatibility List: Will be released with Beta 2. (For now visit the website or see below)

Download: https://p081.github.io

Project 081 is a simple to use unofficial Mac OS X modification by speedie which can install Tiger on some specific models. (see support below)
It is a continuation of the older and flawed The81Project which too allowed you to install Tiger on 2008 Macs.
No features were dropped. Only use The81Project if Project 081 doesn't work (since it's a beta currently)
It offers

    * Close to vanilla experience without days of tinkering
    * Many different patched drivers to get more things functional
    * Next to perfect compatibility
    * No bootloader needed before and after installation
    * One disk image, works on both supported and unsupported Macs (doesn't install unnecessary patches)
    * Package included which automatically installs necessary patches.

## Compatibility

On any version of Mac OS X, installed or recovery, open the terminal and run sysctl hw.model

It should report back one of the following:

### Desktop
##### iMac8,1
##### MacPro3,1
##### XServe2,1

### Laptop
##### MacBook3,1
##### MacBook4,1
##### MacBookAir1,1

If it's not one of these, it's either too new or natively supported.

## Issues

For MacBookAir1,1, MacBook3,1, MacBook4,1, XServe2,1 users:
No GPU Acceleration which may cause slowdown.

For iMac8,1 users
Everything works, but DO NOT install the AirPort 2010 update
It may brick your wireless forcing you to reinstall.


By using this tool, both patcher, patches and/or images, you are 100% using them at your own risk. In case your machine fails to boot, your important data is lost and you get fired from work, you have no one to blame but yourself. Please.. whatever you do. Tinker responsibly!

## Simple instructions

Simply grab a simple 8GB or larger USB stick, go to https://p081.github.io in any browser, click on the Download section and download your image. Then you can use Disk Utility (Built into Mac OS X), or balenaEtcher (macOS, Linux, Windows) to write the DMG to a USB flash drive! Download it from here: https://github.com/balena-io/etcher

## Booting

Enter the boot menu on your Early 2008 Mac (By powering on the computer and holding ⌥ until you see a while screen) Select the Project 081 volume (which may have a different name depending on what version you're using). Then erase your disk and install as normal. Patches will be applied automatically if available.
Fixing issues

A lot of issues cannot be fixed. If your Mac has Intel GMA X3100 graphics for example, it will not get any GPU acceleration. Take a look at the Compatibility List and before you report an issue, make sure it's not already listed. Most Macs will not have perfect compatibility.. yet.. If your issue isn't listed in the Compatibility list:

Contact me on Discord (speedie#8260) or on Twitter (@spdgmr)

## Troubleshooting

For most people, this would work instantly, but maybe with some issues if you have one of the models listed above.

If you have an iMac8,1 or MacBookPro4,1 and you aren't getting any sound, you may have picked the wrong image.
Those machines need a special image so download the BLUE one. If it still doesn't work, contact me.

If you can't boot with a MacPro3,1, do note that a lot of GPUs aren't compatible. For the best results, use official original GPUs.
Known supported GPUs: Radeon HD 2600XT

## Download

Latest version is of course the latest GitHub release in this repository.
You can download it by visiting https://github.com/p081/Project081/releases/latest
Otherwise visit https://p081.github.io for the most up to date download and where most people download.

## Credit

See our website for up-to-date credits.

## For more information

Visit out website, it always has the most up-to-date information
Otherwise, contact me.

