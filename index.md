---
layout: default
---



<!--
![image]({{site.baseurl}}/img/JLS_round.png "image of J. Le Sommer"){:width="200px" style="float: right"}
-->

<br>

I am an **atmospheric physicist** working on Earth system modelling at the Centre National de Recherches Météorologiques ([CNRM](https://www.umr-cnrm.fr/)), Toulouse, France, the research laboratory of Météo-France, jointly led by the CNRS. My research focuses on the **interactions between atmospheric processes** (e.g., turbulence, convection, clouds, radiation) **and the larger-scale circulation of the atmosphere**, with an appetite for **tropical regions**. Such interactions are at the core of atmospheric modelling, including the development of so-called **parameterizations of physical processes, their integration in climate models, and their evaluation**.

<br>

<!--
## Interested in working with me ? 
Research appointments will be **considered at any time** for candidates with an outstanding profile. A number of schemes are available for funding **PhD** or **postdoctoral positions**. Interested applicants should contact me by email. 
-->

## Recent posts
{% for post in site.posts limit:2%}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}


