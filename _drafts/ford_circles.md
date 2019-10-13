---
layout: post
title:  "Ford Circles"
---
Ford circles are a family of circles which are tangent to the horizontal axis at $x = \frac{p}{q}$, with a radius of $\frac{1}{2q^{2}}$. These circles can be generated employing an unusual form of addition named after John Farey, Sr.

Farey addition can be used to sum two reduced fractions, by adding their numerators and denominators separately, as demonstrated below:

$$\frac{1}{2} \oplus \frac{1}{3} = \frac{(1 + 1)}{(2 + 3)} = \frac{2}{5}$$

It can be seen that the circle at $x = \frac{1}{2}$ and the circle at $x = \frac{1}{3}$ will generate a new, smaller circle inscribed between them and the horizontal axis, at $x = \frac{2}{5}$!

Drag the slider to generate successive generations of Ford circles.

{% include js_project_embed.html project_name='ford_circles' %}

## Resources

#### Numberphile - Funny Fractions and Ford Circles
Francis Bonahon plays around with Farey addition, and shows its geometric analog, Ford circles.

{% include youtube_embed.html id='0hlvhQZIOQw' %}

#### Coding Train - Recursion
Daniel Shiffman discusses recursion, and implements recursion visually using [p5.js](https://p5js.org/).

{% include youtube_embed.html id='jPsZwrV9ld0' %}
