![image](https://github.com/user-attachments/assets/b7b14ac2-6cdf-47de-9cf2-c0ab0a8d80d9)

```html
{% block extra_head %}
<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
{% endblock %}
```


```html
<div id="three-container" class="position-fixed top-0 start-0 w-100 h-100"></div>
```

```html
<script src="{% static 'js/threeScene.js' %}"></script>
```
