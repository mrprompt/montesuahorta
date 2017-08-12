---
layout: default
slug: index
---
<!--start: Container -->
<div class="container">
	<!-- Blog Posts -->
	<div class="row">
		<h1>Passo a Passo</h1>

		{% for image in site.images %}
			<img src="{{ file.url }}" />
		{% endfor %}
	</div>
	<!-- /Blog Posts -->
</div>
<!--end: Container-->