---
layout: post
title:  "Hello World."
date:   2016-03-10 14:00:00 +0000
categories: health
feature_image_url: https://d13yacurqjgara.cloudfront.net/users/194727/screenshots/2718613/dailyui_003.png
---
I've recently been overwhelmed at how much work I've been taking on. My final year of College has been crazy hectic so I'm making this blog as a bit of an outlet and to show off some of the things I've been working on. Games, Websites, audio clips, writing and anything else creative I want to work on.

To start off I've made this site running on Jekyll, which lets me write markdown and it parses it as html like:

- code snippets
- links
- images
- text

`This is a block` followed by a code block:

{% highlight javascript %}
function helloWorld(){
  var x = "hello";
  var y = "world";
  console.log(x + " " + y);
  // prints out "hello world"
}
{% endhighlight %}

{% highlight C# %}
public void Start(GameObject gc){
  public GameObject player = GameObject.FindWithTag("Player");
  gc.GetComponent<ScriptName>();
  Debug.Log(gameObject.transform.position);
  // Hello
}
{% endhighlight %}

This is a [link][link_name]. I loooove the way you can define links with jekyll, it works kind of like a bibliography, where they're defined at the bottom and just referenced like this:
{% highlight markdown %}
  This is a [link][link_name]

  [link_name]: http://google.com
{% endhighlight %}

That's all for now, gonna do some Unity stuff later maybe and update again soon.

[link_name]: http://google.com
