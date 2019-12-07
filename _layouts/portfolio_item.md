---
layout: default
---
<h3>{{ page.title }}</h3>
<div class="portfolio-icon">
	<img class="portfolio-icon-image card-img-top" src="/assets/images/{{page.logo}}" alt="Card image cap">
</div>    	 
<p class="card-text">{{page.description}}</p>
{% if page.code %}
<a href="{{page.code}}" target="_blank">
	<button type="button" class="btn btn-sm btn-outline-secondary">Code</button>
</a>
{% endif %}
{% if page.website %}
<a href="{{page.website}}" target="_blank">
	<button type="button" class="btn btn-sm btn-outline-secondary">Website</button>
</a>
{% endif %}