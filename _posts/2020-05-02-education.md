---
title: Education must also train one for quick, resolute and effective thinking.
date: 2020-05-02 15:04:46 Z
categories:
- Lifestyle
- craft
tags:
- code
toc: true
beforetoc: Prism highlighter is a very powerful thing. In this article I'm going to
  show you what you can actually do with it, some tricks and tips while editing your
  post. Tocs is also enabled as you can see in summary.
layout: post
author: muhammed ashfar
image: "/assets/images/3.jpg"
---

Memoirs theme has Prism highlighter integrated. I will show you in this post a few examples of how it looks if you are a developer planning to add pieces of code on your website.


#### HTML

```html
<li class="ml-1 mr-1">
    <a target="_blank" href="#">
    <i class="fab fa-twitter"></i>
    </a>
</li>
```

#### CSS

```css
.highlight .c {
    color: #999988;
    font-style: italic;
}
.highlight .err {
    color: #a61717;
    background-color: #e3d2d2;
}
```

#### JS

```js
// alertbar later
$(document).scroll(function () {
    var y = $(this).scrollTop();
    if (y > 280) {
        $('.alertbar').fadeIn();
    } else {
        $('.alertbar').fadeOut();
    }
});
```

#### Python

```python
print("Hello World")
```

#### Ruby

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

#### C

```c
printf("Hello World");
```
