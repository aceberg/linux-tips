---
layout: post
title: "Enable beep in Ubuntu"
date: 2021-01-30 12:25:06
tags:
 - ubuntu
 - desktop
---

To enable beep in Ubuntu:

{% raw %}
apt install beep
{% endraw %}

in /etc/modprobe.d/blacklist.conf
comment:
{% highlight bash %}
blacklist pcspkr
{% endhighlight bash %}

modprobe pcspkr
