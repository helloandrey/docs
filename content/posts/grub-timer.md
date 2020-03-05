---
title: "How to set GRUB timeout to zero"
tags: [grub,config]
date: 2020-01-03T01:31:39+03:00
---

Edit `GRUB_TIMEOUT=0` line in `/etc/default/grub` configuration file, then run following command to apply the changes:
```
grub-mkconfig -o /boot/grub/grub.cfg
```
