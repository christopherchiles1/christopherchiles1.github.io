---
layout: post
title:  "Ford Circles"
---
In Arithmetic, we are taught that in order to add fractions, we must first find their least common factor, and multiply each fraction by that factor over itself in order to get a common denominator... this ensures that we get the correct value for our addition, so:

{% katex display %}
\frac{1}{2} + \frac{1}{3} = \frac{1}{2}\left(\frac{3}{3}\right) + \frac{1}{3}\left(\frac{2}{2}\right) = \frac{3}{6} + \frac{2}{6} = \frac{5}{6}
{% endkatex %}

However, in mathematics we can define whatever operations we want, so long as we can get others to agree! What if we let ourselves add fractions simply by adding their numerator and denominator, respectively? Would this just produce nonsense, or can we find some analog between this new form of addition and reality?

Let's start by defining our new form of addition. In the example given above, we would do the following:

{% katex display %}
\frac{1}{2} \oplus \frac{1}{3} = \frac{(1 + 1)}{(2 + 3)} = \frac{2}{5}
{% endkatex %}

This is named Farey addition, after Farey (Insert more historical research here).

{% include js_project_embed.html project_name='ford_circles' %}

## Resources

#### Numberphile: Funny Fractions and Ford Circles
In this video, Francis Bonahon plays around with Farey addition, and shows its geometric analog, Ford circles.

{% include youtube_embed.html id='0hlvhQZIOQw' %}

#### Coding Train: Recursion
In this video, Daniel Shiffman discusses recursion, and implements recursion visually using [p5.js](https://p5js.org/). When I saw this video, it gave me the idea to code up the Ford circles from Numberphile in an interactive way, using p5.

{% include youtube_embed.html id='jPsZwrV9ld0' %}
