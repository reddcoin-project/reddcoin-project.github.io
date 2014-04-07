---
layout: post
title: New development blog
author: Mathy Vanvoorden
---

In order to communicate better with our users we have created this developer blog. Here useful information on development will be shared as it is a bit more of a static medium than the [development subreddit](http://www.reddit.com/r/redddev/). We will keep using that subreddit to gather information and get discussions going though.

-----

This blog is created using the excellent [Jekyll](http://jekyllrb.com) system and hosted on [Github Pages](http://pages.github.com/).

The basic setup was copied from [Poole](http://getpoole.com/), the Jekyll butler. Because the basic layout is very minimalistic it allows the community to do what it does best: create a new design in line with the main Reddcoin website. I have intentionally not changed anything (except the favicon) to allow the creative juices to flow.

If you want to contribute to the blog you can do so in the following way:

* Make sure ruby 1.9.3 or 2.0.0 is installed

{% highlight bash %}
ruby --version
{% endhighlight %}

* If you install ruby gems in your user directory (I recommend it) and not system wide, add the bin dir to the path

{% highlight bash %}
echo export PATH="~/.gem/ruby/2.0.0/bin/:${PATH}" >> ~/.bashrc
source ~/.bashrc
{% endhighlight %}

* clone the Github pages repository somewhere (or create your own fork and clone that)

{% highlight bash %}
git clone https://github.com/reddcoin-project/reddcoin-project.github.io
cd reddcoin-project.github.io/blog
{% endhighlight %}

* install bundler  

{% highlight bash %}
gem install bundler
{% endhighlight %}

* install requirements

{% highlight bash %}
bundle install
{% endhighlight %}

* update          

{% highlight bash %}
bundle update
{% endhighlight %}

* start a local copy    

{% highlight bash %}
bundle exec jekyll serve
{% endhighlight %}

Now you are set! Just edit the pages as you see fit, check the Jekyll documentation and send us patches or create pull requests! Also if you feel something is worth sharing you can create your own blog post and send it to us for inclusion.
