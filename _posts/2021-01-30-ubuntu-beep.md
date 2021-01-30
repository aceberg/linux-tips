---
layout: post
title: "Enable beep in Ubuntu"
date: 2021-01-30 12:25:06
tags:
 - ubuntu
 - desktop
---

To enable beep in Ubuntu:

apt install beep

in /etc/modprobe.d/blacklist.conf
comment:
blacklist pcspkr

modprobe pcspkr
