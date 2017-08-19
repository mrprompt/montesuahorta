---
layout: default
slug: composteira-pet
tags: compostagem,composteira,garrafa,pet
---
# Composteira com Garrafa Pet

### Material Necessário
- Garrafa Pet (qualquer tamanho, desde que formem pares do mesmo tamanho)
- Estilete
- Tesoura
- Britas
- Terra
- Minhocas (opcional)
- Restos de legumes e verduras (exceto cozidos e carnes)
	
### Passo a Passo

{% assign image_files = site.static_files | where: "image", true | where: "composteira", true %}
{% for myimage in image_files %}
<img src="{{ myimage.path }}" alt="Passo a passo" class="img-responsive thumbnail">
{% endfor %}
