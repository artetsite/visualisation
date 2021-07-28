# Visualisation de données Art et site

Page web de documentation du travail de visualisation des données art et site. 


Groupe de travail: 
- [Aziz Boughedir](https://histart.umontreal.ca/repertoire-departement/doctorants/doctorant/in/in31707/sg/Aziz%20Boughedir/)
- [Lena Krause](https://lenamk.site/)
- [Suzanne Paquet](https://histart.umontreal.ca/repertoire-departement/professeurs/professeur/in/in15408/sg/Suzanne%20Paquet/)
- [Christelle Proulx](https://histart.umontreal.ca/repertoire-departement/doctorants/doctorant/in/in30304/sg/Christelle%20Proulx/)



## Article Sens Public

Article à paraître dans la revue *Sens Public*: «Devenir-destination et photographies (en ligne) de quelques œuvres d’art : publics actuels du land art», Christelle Proulx et Suzanne Paquet, Département d’histoire de l’art et d’études cinématographiques, Université de Montréal.

Données: 
- [SunTunnels](https://gist.githubusercontent.com/artetsite/5b3f9862628ef44b4d4dab6f34ffff1d/raw/35ed6c1fa45f3b3e1493fa382c14049a98e8ed3d/gistfile1.txt)
- [Broken Circle](https://gist.githubusercontent.com/artetsite/6e040a53d60d68215557bc2b2045e6b9/raw/4a2e31ba539f0ae6d33d5be908425add2b540b59/Broken%25202%2520photos%2520top%2520clean.csv)
- [Lightning Field](https://gist.githubusercontent.com/artetsite/96d9ab8bc0f0b77d7f01d787d378ce94/raw/b47b3360bd3e35028a0f6625ebcc92d54e381987/Lightning%2520Field%25201%2520photo%2520top%2520clean.csv)
- [Photos](https://gist.githubusercontent.com/artetsite/1d1f6bd9613c4599d436995c7a9d3c62)
- Sources des photographies:
  - _Sun Tunnels_, Nancy Holt (1973-1976): [1](https://flic.kr/p/yp1GgD), [2](https://flic.kr/p/y6MM6p), [3](https://flic.kr/p/yoiuQD), [4](https://flic.kr/p/y6GsPd), [5](https://flic.kr/p/yoiuQD)  
  - _Broken Circle / Spiral Hill_, Robert Smithson, (1971): [6](https://flic.kr/p/cZLtQS), [7](https://flic.kr/p/cZLtQS)
  - _The Lightning Field_, Walter de Maria (1977): [8](https://flic.kr/p/cZJQ9f)

CSS:
- [fichier CSS complémentaire](./artetsite.css) (pour les iframes)


### Nombre de vues - Sun Tunnels

<iframe width="100%" height="584" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/line-chart-fig2?cells=chart"></iframe>

Lien vers le [Notebook](https://observablehq.com/@artetsite/line-chart-fig2)

[Essai avec un diagramme de barres](https://observablehq.com/@artetsite/vues-sun-tunnels)


### Carte _Sun Tunnels_

<iframe width="100%" height="756" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos-test-styles-embed?cells=chart%2Clegendaire"></iframe>

Problèmes et observations: Palau n'est pas un pays dans le fichier geojson employé



Essais précédents: 
- [Premier essai pour la carte](https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos-tests?cells=chart%2Clegendaire)
- [Essai deux: couleurs + légende](https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos?cells=chart%2Clegende)


### Carte _Broken Circle_

<iframe width="100%" height="581" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-broken-circle-2-photos?cells=chart%2Clegendaire"></iframe>

Lien vers le [Notebook](https://observablehq.com/@artetsite/line-chart-fig2)


### Carte _Lightning Field_ 

<iframe width="100%" height="581" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-lightning-field-1-photo/2?cells=chart%2Clegendaire"></iframe>


Lien vers le [Notebook](https://observablehq.com/@artetsite/carte-broken-circle-2-photos)


## Production d'une nouvelle carte

Étapes: 
- _Fork_ une carte qui fonctionne
- Changer le titre
- Changer l'url des données _Gist_
- Changer l'url des images
- Adapter l'échelle + choisir les couleurs


## Références

### Références Observable & D3.js

Couleurs
- Production de palettes de couleur: [coolors](https://coolors.co/)
- [Image color picker](https://imagecolorpicker.com)
- [Dégradés de couleurs D3.js](https://github.com/d3/d3-scale-chromatic)

Fonctionnement des échelles
- [Documentation D3.js](https://observablehq.com/@d3/continuous-scales)


### Outils utilisés

[D3.js](https://d3js.org/) dans [Observable HQ](https://observablehq.com/@artetsite)

[Github](https://github.com/artetsite): 

- Gist pour les données (attention à bien mettre l'url du gist à jour en cas de changement)
- Page web en markdown, publiée avec Jeckyll et Github Pages

### Bibliographie

- [Créer un atlas numérique de l’architecture publique en France (1795-1840)](http://lenamk.site/memoire/), Lena Krause, 2021: en particulier le chapitre 3 pour les expérimentations avec des viusalisations interactives


## Inspiration

### Cartes

<iframe width="100%" height="1038" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/pen-and-ink-stipple-effect?cells=test"></iframe>

