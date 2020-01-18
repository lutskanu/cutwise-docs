---
title: Ray path in Round Diamond. How Stereo defines Round Diamond performance
date: 2020-01-15 00:00:00
description: Let’s consider optical theory for arrow facet under the table. Right eye see white flash reflected from the light source on the right.

featured_image: ''
---

Let’s consider optical theory for arrow facet under the table. Right eye see white flash reflected from the light source on the right.

![](/images/page1-pic1.png)

The same area is black for left eye, because it **see the observer’s head reflection**.

So in one area of space our eye see very different and contradictive images:
* — white light source reflection flash
* — and black head reflection.
Difference in signal intensity is more than 1000 times.

![](/images/page1-pic2.png)

#### How Round Diamond Cut works?

We described how the Tolkowsky Round works. Let’s check now Rounds with different proportions.
What will happened if we will decrease or increase Pavilion angle.

<p align="center">
Tolkowsky
</p>

<p align="center">
<iframe
    name="Cutwise Player"
    width="480"
    height="480"
    frameborder="0"
    src="https://widget.cutwise.com/video/37814?sp=11"
    allowfullscreen
></iframe>
</p>
<p align="center">
Ca 34.5, Pa 40.8
</p>

We will check two shallower stones. One with Pa 39.6 and another very shallow.
And two deeper stones: one with Pa 41.6, and another very deep “Nail Head” diamond.

|   |  |               |    |    |
| Very Shallow    | Shallow | Tolkowsky              | Deep   | “Nail Head” |
| <iframe name="Cutwise Player" width="240" height="240" frameborder="0" src="https://widget.cutwise.com/video/37814?sp=11" allowfullscreen></iframe>   | <iframe name="Cutwise Player" width="240" height="240" frameborder="0" src="https://widget.cutwise.com/video/37814?sp=11" allowfullscreen></iframe> | <iframe name="Cutwise Player" width="240" height="240" frameborder="0" src="https://widget.cutwise.com/video/37814?sp=11" allowfullscreen></iframe>   | <iframe name="Cutwise Player" width="240" height="240" frameborder="0" src="https://widget.cutwise.com/video/37814?sp=11" allowfullscreen></iframe>  |    <iframe name="Cutwise Player" width="240" height="240" frameborder="0" src="https://widget.cutwise.com/video/37814?sp=11" allowfullscreen></iframe>     |
| Ca 25 Pa 39 | Ca 34.5, Pa 39.6 | Ca 34.5, Pa 40.8   | Ca 34.5, Pa 41.8   | Ca 34.5, Pa 43.6 |



**Obviously,** we’ve styled up *all the basic* text formatting options [available in markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

You can create lists:

* Simple bulleted lists
* Like this one
* Are cool

And:

1. Numbered lists
2. Like this other one
3. Are great too

You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”

The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| Duet Jekyll Theme    | Jekyll Themes | Yes              | $49   |
| Index Jekyll Theme   | Jekyll Themes | Yes              | $49   |
| Journal Jekyll Theme | Jekyll Themes | Yes              | $49   |

And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too:

---

#### Image galleries

Here's a really neat custom feature we added – galleries:

{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,
	"
%}

Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a simple Liquid snippet in your post to create a masonry grid image layout:

{% raw %}
```liquid
{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,
	"
%}
```
{% endraw %}

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.


#### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg
	"
%}

#### What about videos?

Videos are an awesome way to show off your work in a more engaging and personal way, and we’ve made sure they work great on our themes. Just paste an embed code from YouTube or Vimeo, and the theme makes sure it displays perfectly:

{% include post-components/video.html
	url = "https://player.vimeo.com/video/270725085?color=6c6e95&title=0&byline=0"
	full_width = true
%}

### Pretty cool, huh?

We've packed this theme with powerful features to show off your work.
Why not put them to use on your new website?

<a href="https://jekyllthemes.io/theme/made-portfolio-jekyll-theme" class="button--fill">Get This Theme</a>
