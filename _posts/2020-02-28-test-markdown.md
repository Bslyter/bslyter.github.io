---
layout: post
title: An Adventure
subtitle: 65 Million Years in the Making
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

Demo post about absolutely nothing. If you want to make a post about nothing using markdown, [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading-- blah, blah, blah

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Hundred | Twenty |
| Five | Thousand | Six |
| Hundred | Minutes | Blah |
| Blah | Blah | Blah |


How about a yummy goat?

![Goat](https://www.gamespot.com/images/1300-2840589)

It can also be centered!

![Goat](https://www.gamespot.com/images/1300-2840589){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
