---
layout: page
title: Photos
permalink: /photos/
toggle: on
rank: 6
---

<div class="lab-wrapper">
    <ul class="lab-list">
    <!-- show photos -->
    {% for photo in site.data.evens %}
        {% if photo.name and photo.time %}
            {% include photo.html %}
        {% endif %}
    {% endfor %}
    </ul>
</div>
