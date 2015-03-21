---
layout: post
title:  "GitHub Pages公開"
date:   2015-03-21 22:00:00
categories: github
---
* 前提
	* [jekyllのインストール](/jekyll/2015/03/21/jekyll-install.html 'jekyllのインストール')が終わっていること

* GitHubの「New Repository」からリポジトリを作成する。
	* Repository name: moriyasu0410.github.io

* GitHubへpushする。
{% highlight sh %}
$ cd moriyasu0410.github.io
$ git init
$ git add .
$ git commit -m 'first commit'
$ git remote add origin git@github.com:moriyasu0410/moriyasu0410.github.io.git
$ git push -u origin master
{% endhighlight %}

* ブラウザを起動し、http://moriyasu0410.github.io/へアクセスする
{% highlight sh %}
http://moriyasu0410.github.io/
{% endhighlight %}
