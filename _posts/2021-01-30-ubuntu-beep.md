---
layout: post
title: "Enable beep in Ubuntu"
date: 2021-01-30 12:25:06
tags:
 - ubuntu
 - desktop
---

To enable beep in Ubuntu:

{% highlight bash %}
# apt install beep
{% endhighlight %}

in /etc/modprobe.d/blacklist.conf
comment:
>/etc/modprobe.d/blacklist.conf
{:.filename}
{% highlight bash %}
blacklist pcspkr
{% endhighlight bash %}

{% highlight bash %}
modprobe pcspkr
{% endhighlight %}
