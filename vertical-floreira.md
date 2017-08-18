---
layout: default
slug: vertical-floreira
---
# Vertical com Floreiras

### Material Necessário
- Floreiras (qualquer tamanho e quantidade)
- Corda
- Presilhas
- Broca 4mm a 8mm
- Estilete
- Tesoura
- Furadeira de mão
- Parceiro(a) compreensivel com a sujeira
- Britas (ou pedaços de telha, argilha expandida, isopor e etc)
- Pano (qualquer tecido que permita que a água passe)
	
### Passo a Passo

{% assign image_files = site.static_files | where: "image", true | where: "vertical", true %}
{% for myimage in image_files %}
<img src="{{ myimage.path }}" alt="Passo a passo" class="img-responsive thumbnail">
{% endfor %}
