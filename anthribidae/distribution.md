---
layout: default
title: Distribution
has_children: true
nav_order: 3
---


# Distribution of Anthribidae 
{: .no_toc }

Biogeographic regions according to [Holt et al. (2013)](https://www.science.org/doi/10.1126/science.1228282). 

 https://api.gbif.org/v2/map/occurrence/density/{z}/{x}/{y}@1x.png?taxonKey=212&bin=hex&hexPerTile=30&style=classic-noborder.poly 
 
 {% leaflet_map %}
    {% leaflet_marker { "latitude" : 41.881832,
                       "longitude" : -87.623177,
                       "popupContent" : "Hello World from Chicago!"} %}
{% endleaflet_map %}

