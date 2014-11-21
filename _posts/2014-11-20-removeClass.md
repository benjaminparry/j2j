---
layout: function
title: "removeClass"
category: function
date: 2014-11-20 19:40:12
mozlink: https://developer.mozilla.org/en-US/docs/Web/API/Element.classList
mozLabel: Element.classList
polyfill: https://github.com/remy/polyfills/blob/master/classList.js
polyfillLabel: classList
canIUse: classList
---

#### jQuery
{% highlight javascript %}
$(element).removeClass("className1 className2");
{% endhighlight %}

#### Native JavaScript for IE 9 +
{% highlight javascript %}
element.classList.remove("className", "secondClassName");
{% endhighlight %}

#### Native JavaScript for IE 8
You can use the above code along with the `classList` pollyfill.