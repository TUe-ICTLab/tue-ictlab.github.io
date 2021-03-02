**Welcome to the GitHub page of the Information and Communication Theory Lab**

For more information about our group, check the following websites:
- https://www.sps.tue.nl/ictlab/
- https://www.tue.nl/ictlab/

List of available GitHub repositories:

{% for repository in site.github.public_repositories %}
{% unless repository.name == "tue-ictlab.github.io" %}
* [{{ repository.name }}]({{ repository.html_url }})
{% endunless %}
{% endfor %}
