---
layout: post
title:  "jekyllのインストール"
date:   2015-03-21 16:00:00
categories: jekyll
---
* 前提
	* OS X 10.9.5
	* Ruby 2.1.0

* 公式サイト
	* [jekyll](http://jekyllrb.com)

* jekyllをインストールする
{% highlight sh %}
$ gem install jekyll
{% endhighlight %}

* jekyllのバージョンを確認する
{% highlight sh %}
$ jekyll -v
{% endhighlight %}

* 雛形を作成する
{% highlight sh %}
$ jekyll new moriyasu0410.github.io
{% endhighlight %}

* ローカル環境で動作確認する
{% highlight sh %}
$ jekyll serve --watch
{% endhighlight %}

* ブラウザを起動し、http://127.0.0.1:4000/へアクセスする
{% highlight sh %}
http://127.0.0.1:4000/
{% endhighlight %}
