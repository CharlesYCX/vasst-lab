---
title: "VASST Lab - Pictures"
layout: piclay
excerpt: "VASST Lab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Robarts](#robarts), [Western University](#western), [Imaging Technology](#imaging), [Lab Team](#lab)


## Lab Team
From the [VASST Lab](https://www.robarts.ca/peterslab/people/index.html).

#### Taylor Dinner - November 2023 - VASST Lab Group Photo
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/TaylorDinner_Nov2023_VASST_Lab_GroupPhoto.jpeg" width="60%">
</figure>

#### Taylor Dinner - November 2024 VASST Lab Group Photo
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/TaylorDinner_Nov2024_VASST_Lab_GroupPhoto.jpg" width="60%">
</figure>


## Robarts

#### Welcome to the [Robarts Research Institute](https://www.youtube.com/watch?v=SbyUp5ar1A0)
<iframe width="560" height="315" src="https://www.youtube.com/watch?v=SbyUp5ar1A0" frameborder="0" allowfullscreen></iframe>

#### Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>

First advertisement.
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageLeiden_red.jpg" width="60%" >
</figure>


## Western University
From the [group of ](http://www.qudev.ethz.ch/).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageETH_red.jpg" width="60%">
</figure>

## Imaging Technology
From the [group of ](http://davisgroup.lassp.cornell.edu).
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/WebpageCornell_red.jpg" width="60%">
</figure>

