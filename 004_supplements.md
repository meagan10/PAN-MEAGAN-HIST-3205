---
layout: default
title: Supplements
number: 4
---

# Supplements

Do you have supplementary materials (such as media files) or links for further information for the reader? (minimum 3 additional media files or links)

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1KgAZAHQakArenVVkXmVzurk0hmcpfSpfU_IpufMWhMw&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

# Supplementary Websites

Place your links here to websites that have information about your topic.
I copied this text from this [website](https://www.lipsum.com/feed/html) 

# Supplementary Media Files

Insert videos or images here.

*Hungarian Declaration of Independence, April 14, 1849.*

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'HungarianDeclarationOfIndependence'" %} {% include media.html pages=media %}

*Videos*

{% assign media = site.media_metadata | where_exp: "item", "item.name == '1848RevolutionsVideo'" %} {% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'Unifications'" %} {% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'DreyfusAffair'" %} {% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'NationalismAPEuro'" %} {% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'NationalismWWI'" %} {% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'TheCulturalCode'" %} {% include media.html pages=media %}
