---
layout: function
title: "toggleClass"
category: function
date: 2014-11-20 19:12:26
mozlink: https://developer.mozilla.org/en-US/docs/Web/API/Element.classList
mozLabel: Element.classList
polyfill: https://github.com/remy/polyfills/blob/master/classList.js
polyfillLabel: classList
canIUse: classList
---

#### jQuery
{% highlight javascript %}
$(element).toggleClass("className1");
{% endhighlight %}

#### Native JavaScript for IE 10 +
{% highlight javascript %}
element.classList.toggle("className");
{% endhighlight %}

#### Native JavaScript for IE 8 and 9
You can use the above code along with the `classList` pollyfill.