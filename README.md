<img width="256" alt="Project081" src="https://user-images.githubusercontent.com/71722170/124338538-d20d2e80-dba8-11eb-813a-846e37cfd656.png">

# Project 081

**NOTE: Project 081 is no longer being worked on. I know this may be disappointing for some of you, but I do not have time to maintain a project I do not use, and a project which is never going to be perfect anyway. I am going to keep the project up for anyone who wants to use it, but I will not be providing support to anyone requesting it.**

Project 081 is a simple to use unofficial Mac OS X modification which can install Tiger on some specific models. (see support below)

## Goals of Project 081

- Close to vanilla experience without days of tinkering
- Many different patched drivers to get more things functional
- No bootloader needed before and after installation
- One disk image, works on both supported and unsupported Macs (doesn't install unnecessary patches)

## Quick Links
- [Wiki](https://github.com/p081/wiki/wiki)
- [Installation Guide](https://speedie.gq/projects/p081-install-guide.php)

## Compatibility

On any version of Mac OS X, installed or recovery, open the terminal and run `sysctl hw.model`

It should report back one of the following:

### Desktop

- iMac8,1
- MacPro3,1
- XServe2,1

### Laptop

- MacBook3,1
- MacBook4,1
- MacBookPro4,1
- MacBookAir1,1

If it's not one of these, it's either too new or natively supported.

## Issues

- MacBookPro4,1 users: Fails to boot the installer, see issue #3
- MacBookAir1,1, MacBook3,1, MacBook4,1, XServe2,1: No GPU Acceleration which may cause minor slowdown with GPU heavy tasks.
- iMac8,1, maybe MacBookPro4,1: Installing the AirPort 2010 update breaks ethernet and wireless.

## Hackintosh

Nope, nope. Wrong place for that.

## Credit

See our [website](https://speedie.gq/projects/project081.php) for up-to-date credits.

## Licensing

The goal is to make everything as free as possible. However due to Apple's full operating system being **absolutely proprietary**, there is no source code for Mac OS X Tiger to speak of.
