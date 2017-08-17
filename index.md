---
layout: default
slug: index
---
<!--start: Container -->
<div class="container">
	<!-- Blog Posts -->
	<div class="row">
		<h1>Passo a Passo - Vertical com Floreiras</h1>

		{% assign image_files = site.static_files | where: "image", true | where: "vertical", true %}
		{% for myimage in image_files %}
		<img src="{{ myimage.path }}" alt="Passo a passo" class="img-responsive thumbnail">
		{% endfor %}
	</div>
	<!-- /Blog Posts -->

	<!-- Blog Posts -->
	<div class="row">
		<h1>Passo a Passo - Vertical com Garrafas Pets</h1>

		{% assign image_files = site.static_files | where: "image", true | where: "pet", true  %}
		{% for myimage in image_files %}
		<img src="{{ myimage.path }}" alt="Passo a passo" class="img-responsive thumbnail">
		{% endfor %}
	</div>
	<!-- /Blog Posts -->
</div>
<!--end: Container-->