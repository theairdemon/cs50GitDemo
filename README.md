## Welcome to the CS50 Git Demo!

{% for image in site.static_files %}
    {% if image.path contains 'images/' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}
