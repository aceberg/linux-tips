---
layout: post
title: "Enable beep in Ubuntu"
date: 2021-01-30 12:25:06
share: true
tags: ubuntu desktop
---

To enable beep in Ubuntu:

{% highlight bash %}
apt install beep
{% endhighlight %}

In /etc/modprobe.d/blacklist.conf comment:
>/etc/modprobe.d/blacklist.conf
{:.filename}
{% highlight bash %}
# blacklist pcspkr
{% endhighlight bash %}

Then run:

{% highlight bash %}
modprobe pcspkr
{% endhighlight %}
