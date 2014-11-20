---
layout: function
title: "removeClass"
category: function
date: 2014-11-20 19:40:12
mozlink: https://developer.mozilla.org/en-US/docs/Web/API/Element.classList
mozLabel: Element.classList
pollyfill: https://github.com/remy/polyfills/blob/master/classList.js
pollyfillLabel: classList
canIUse: classList
---

#### jQuery
{% highlight javascript %}
$(element).removeClass("className1 className2");
{% endhighlight %}

#### Native JavaScript
{% highlight javascript %}
element.classList.remove("className", "secondClassName");
{% endhighlight %}