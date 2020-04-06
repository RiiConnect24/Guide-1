---
title: "BlueBomb"
---

{% include toc title="Table of Contents" %}

Αν χρειάζεστε βοήθεια με οτιδήποτε σχετικά με αυτό τον οδηγό, επισκεφθείτε το [Wii mini Hacking Discord](https://discord.gg/6ryxnkS) (προτείνεται)
{: .notice--info}

![BlueBomb](/images/bluebomb.png)

Bluebomb is an exploit that takes advantage of a flaw in the Wii and Wii mini's Bluetooth libraries. Although it is the only exploit that works for the Wii mini, BlueBomb can run on the original Wii as well. This exploit also enables recovery from certain bricks, such as a banner brick.

For the original Wii, we recommend using [another exploit](/get-started) instead if you intend to install the Homebrew Channel and/or BootMii.
{: .notice--info}

This exploit will not work on a Wii U's vWii. Please follow [this guide](https://wiiuguide.xyz/#/vwii/) instead.
{: .notice--warning}

#### Section I - What you need
- A Linux machine
  - If you are using a Chromebook, you do not need to install another Operating System; instead, enable [Linux in ChromeOS](https://support.google.com/chromebook/answer/9145439?hl=en).
  - If you have a Raspberry Pi, you can use that instead as it most likely has Linux preinstalled.
  - Using Windows Subsystem for Linux will **not** work, due to the inability to access `systemctl`.
  - If you do not have Linux, [Ubuntu](https://ubuntu.com/download/desktop) is the most user-friendly option
    - 32-bit devices will require [Ubuntu 16.04](http://releases.ubuntu.com/16.04/)
    - For 64-bit devices it is recommended to use the LTS edition due to its stability, but the latest release works as well.
  - You can [flash a Linux install to a USB flash drive](https://ubuntu.com/tutorials/tutorial-create-a-usb-stick-on-windows#1-overview) if you'd not like to install it to your computer.
- A Bluetooth adapter.
  - An internal Bluetooth adapter will work.
  - If you do not have one, make sure to get one compatible with Linux.
- A USB flash Drive formatted as FAT32.
  - This cannot be the same flash drive used for your Linux Machine

#### Section II - Performing the exploit
1. Download the HackMii installer from [the BootMii website](https://bootmii.org/download/).
2. Unpack it and place the `boot.elf` file in your flash drive.
3. Connect the flash drive to the console. For a Wii mini, the USB port is on the back. For a normal Wii, use the bottom port. (or the right port if it's upright).
4. Turn on your console and navigate to the settings menu. On the top right corner you should see a 4-digit code like the one in the picture below. This code is your System Menu version, take a note of this as you will need it later. Afterwards, turn your console off. ![SystemMenuVersion](/images/Wii/SystemMenuVersion.png)
5. Launch your Linux Distro
6. Open the Linux Terminal by pressing `Ctrl + Shift + T`.
7. Run the following commands:
- `wget https://raw.githubusercontent.com/RiiConnect24/Wii-Guide/master/assets/files/bluebomb-helper.sh`
- `chmod +x bluebomb-helper.sh`
- `./bluebomb-helper.sh`
8. The helper will then download the required files, and ask for information about your console.
  - If you have selected a Wii mini you will be asked to provide your region. This can be found in the original packaging, the bottom of the console (RVL-201(EUR) for PAL or RVL-201(USA) for NTSC models) or can be determined by the last digit of the System Menu version (U for NTSC and E for PAL models).
  - If you have selected a Wii you will be asked to provide your System Menu Version that you took note of before.
9. Turn on your console and **do not** connect any Wiimotes.
10. Press the Sync button repeatedly until the terminal shows `got connection handle`

Make sure that the console is close to the computer running the exploit, Ideally it should be less than 3 feet.
{: .notice--info}

The console should now boot to the HackMii installer. You can now shutdown your Linux computer if you are not planning to use it later.

[If using a Wii, proceed to installing the Homebrew Channel and BootMii](hbc)
{: .notice--info}

[If using a Wii mini, proceed to installing the Homebrew Channel](hbc-mini)
{: .notice--info}
