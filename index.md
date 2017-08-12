---
layout: default
slug: index
---
<!--start: Container -->
<div class="container">
	<!-- Blog Posts -->
	<div class="row">
		<h1>Passo a Passo</h1>

		{% assign image_files = site.static_files | where: "image", true %}
		{% for myimage in image_files %}
		<img src="{{ myimage.path }}" alt="Passo a passo" class="img-responsive"/>
		{% endfor %}
	</div>
	<!-- /Blog Posts -->
</div>
<!--end: Container-->