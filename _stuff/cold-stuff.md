---
---

Cold stuff

```html
<header class="short">
    {% include navigation/top.html %}
</header>

<div class="feature-wrapper">
    {% include navigation/feature-nav-selection.html %}
    {% assign left = false %}
    {% for item in page.pitch %}
        {% if item.standalone_heading %}
            <div class="wrapper wrapper-large">
                <h2>{{item.standalone_heading}}</h2>
                {% if item.text %}
                    <p>{{item.text}}</p>
                {% endif %}
            </div>
```