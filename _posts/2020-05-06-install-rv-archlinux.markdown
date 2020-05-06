---
layout: post
title:  "Install RVM on Archlinux in 2020."
date:   2020-05-06 19:00:00 +0200
categories: archlinux rvm
---
For coding with Rails for example and if you are on Archlinux distro, i show you how you can install it on your computer easily.

First step you must to register GPG key on your computer:

{% highlight console %}
gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
{% endhighlight %}

### Basic Install

Now we install stable version of RVM with Ruby:

{% highlight console %}
\curl -sSL https://get.rvm.io | bash -s stable --ruby
{% endhighlight %}

This command line can take some times, you can drink a coffee while waiting...

After this you have the last version by default of Ruby and all is good.

Bye.
