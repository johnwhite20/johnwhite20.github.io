---
layout: post
title: Site Survey
subtitle: First site visit by Mike McCart
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [site survey]
comments: true
author: John White
---

{: .box-success}
Mike McCart from [Glenquicken Roadrecycling](https://glenquickenroadrecycling.co.uk/) carried out a site survey today. 

He explained that the road base needs to be built up in order for water to run off the finshed top surface. Mike identified the field stone we have here as unsuitable for being crushed by the machines they use as part of the work. 

He also told me that there would have to be additional stone delivered to build up the base of the road and more stone added to insure a sound final surface and we would have to ensure water is allowed to flow away from the road and into the fields on either side to prevent future damage. He also explained that the finished road could be kept in good order by adding gravel to any emerging puddles and then the new stone being compacted.

Mike is going to prepare a quote to carry out the work on the road including supplying the additional material needed to form the new surface

**Here is some bold text**

## Here is a secondary heading

[This is a link to a different site](https://deanattali.com/) and [this is a link to a section inside this page](#local-urls).

Here's a table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a yummy crepe?

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg)

It can also be centered!

![Crepe](https://beautifuljekyll.com/assets/img/crepe.jpg){: .mx-auto.d-block :}

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

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
