---
layout: post
title:  "Welcome to Jekyll/myFirstJekyll!"
date:   2016-10-21 02:20:35 +0800
categories: jekyll update
---
<!-- You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
 -->

 <!-- lang: html -->

---
title: 我的第一篇文章
---

# {{ page.title }}

## 目录
+ [第一部分](#partI)
+ [第二部分](#partII)
+ [第三部分](#partIII)

----------------------------------

## 第一部分 <p id="partI"></p>
这里是第一部分的内容

----------------------------------

## 第二部分 <p id="partII"></p>
这里是第二部分的内容

----------------------------------

## 第三部分 <p id="partIII"></p>
这里是第三部分的内容

{{ page.date|date_to_string }}