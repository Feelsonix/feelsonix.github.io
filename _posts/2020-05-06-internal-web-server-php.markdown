---
layout: post
title:  "Internal web server with PHP."
date:   2020-05-06 19:10:00 +0200
categories: programming php
---
After the version 5.4 of PHP, you can use an internal web server for easily testing your website.

For starting this server you just type this command:

{% highlight console %}
php -S localhost:8080
{% endhighlight %}

The advantage of this commmand is that is allows to define configuration variables.
If for example you want to display errors of PHP, you just need to add:

{% highlight console %}
php -S localhost:8080 -ddisplay_errors=1 
{% endhighlight %}

However it is not possible to use URL Rewriting with PHP internal server, this use is reserved to Apache2. However is it possible to specify the folder to use, just typing this command:

{% highlight console %}
php -S localhost:8080 -t public
{% endhighlight %}

Off course you need to have PHP installed on your computer...

Bye.
