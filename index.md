**Welcome to the GitHub page of the Information and Communication Theory Lab**

List of currently available repositories:

{% for repository in site.github.public_repositories %}
{% unless repository.name == "tue-ictlab.github.io" %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endunless %}
{% endfor %}
