---
title: Medium Animals
layout: resultspage
---

<div>
	
{% for p in site.pages %}
	{% if p.size=="medium" %}
    
    <div class="animalname deer">
        <h3>{{ p.title }}</h3>    
    </div>
        
     <div class="animalimg">
		<a href="{{ site.baseurl }}{{ p.url }}">
        		<img src="/web1-categories/{{ p.image }}">  
	     </a>
    </div>
	   {% endif %} 
{% endfor %}

</div>
