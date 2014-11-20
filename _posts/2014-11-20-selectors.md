---
layout: page
title: "Selectors"
category: tut
date: 2014-11-20 19:49:11
---

## ID

#### jQuery
{% highlight javascript %}
var element = $("#my-id");
{% endhighlight %}

#### Native JavaScript
{% highlight javascript %}
var element = document.getElementById("my-id");
{% endhighlight %}

## Class Name

#### jQuery
{% highlight javascript %}
var element = $(".my-class");
{% endhighlight %}

#### Native JavaScript
{% highlight javascript %}
/* Returns an array of elements to loop through.
   This is not supported in IE 8. */
var elements = document.getElementsByClassName("my-class");

/* If you need to support IE 8, use: */
var elements = document.querySelectorAll(".my-class");
{% endhighlight %}

## Attribute

#### jQuery
{% highlight javascript %}
var element = $("input[type=text]");
{% endhighlight %}

#### Native JavaScript
{% highlight javascript %}
/* Returns an array of elements to loop through */
var elements = document.querySelectorAll("input[type=text]"); 

/* Get the first element matching the selector */
var element = document.querySelector("input[type=text]"); 
{% endhighlight %}

## Looping through the matched elements
To loop through the elements matched using `querySelectorAll` or `getElementsByClassName` - 
{% highlight javascript %}
var elements = ...;

for( var i=0; i < elements.length; i++ ) {
	console.log( elements[i] );
}
{% endhighlight %}

`querySelector` and `querySelectorAll` accept a range of [CSS selectors](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_Started/Selectors), such as: 

- `input[type=text]`
- `#my-id .my-class`
- `p.my-class`
- `div > p`