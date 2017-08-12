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
		{{ myimage.path }}
		{% endfor %}
	</div>
	<!-- /Blog Posts -->
</div>
<!--end: Container-->