---
title: Products
permalink: product.html
layout: main
tags: [ mainnav ]
products:
    - Product 1
    - Product 2
    - Product 3
---

{% for product in products %}
- {{ product }}
{% endfor %}