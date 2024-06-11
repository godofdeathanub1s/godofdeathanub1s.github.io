---
title: Linux mint Black Screen / Boot Failure
date: 2024-06-11
categories: [linux]
tags: [linux, troubleshooting]
---

## Introduction 
Did you upgrade your OS recently? And suddenly, when you restarted, it all just went black! O HELL NAAHHHH. But hey, stop there. Don’t panic! I’ve experienced this recently, and today I’m going to teach you how to resolve this issue.
Recently, Linux Mint released a new kernel update, ‘5.15.0–112.’ I was watching some TCM security videos, and I needed to restart my computer because I was troubleshooting some other issues too. I thought everything was normal until my computer screen stayed black for a long minute.

After a long and long research, I’ve figured out that recently I ran a sudo apt upgrade to upgrade my environment not knowing the new release is unstable.

1. First, you gotta restart your computer and spam the `Shift` button.
2. Go to advanced options and boot to your stable backup linux kernel
3. Open your terminal and start removing the unstable linux kernel 5.15.0–112

`sudo apt remove linux-image-5.15.0-112-generic linux-image-unsigned-5.15.0-112-generic linux-modules-5.15.0-112-generic linux-libc-dev linux-modules-extra-5.15.0-112-generic`

4. Update your GRUB and Reboot!

`sudo update-grub; sudo reboot`

Problem solved!
