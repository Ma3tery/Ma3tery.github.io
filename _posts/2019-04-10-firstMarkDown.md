---
layout: post
title:  "FirstMarkDown"
date:   2019-04-10
excerpt: "How to use it!"
tag:
- sample
- post
- video
comments: true
---
##Use '##' to create one title!
Hello world!

##Use 'iframe' tags to link video 
<iframe width="560" height="315" src="https://vd1.bdstatic.com/mda-hfg5qsfzh4792p4r/hd/mda-hfg5qsfzh4792p4r.mp4?auth_key=1554901310-0-0-a7d864ed2dc28f24b33b8bcc2fc2bb16&bcevod_channel=searchbox_feed&pd=bjh&abtest=all" frameborder="0"> </iframe>

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:
##Use '{% highlight html %} and {% endhighlight %}' to create a code block
{% highlight html %}
there are some code !
{% endhighlight %}
