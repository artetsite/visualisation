# Visualisation de données Art et site

Page web de documentation du travail de visualisation des données art et site. 
Notebooks [ObservableHQ](https://observablehq.com/@artetsite?tab=collections)

Groupe de travail: Lena Krause, Christelle Proulx, Aziz Boughedir, Suzanne Paquet



## Article Sens Public

Article à paraître dans la revue *Sens Public*: *Devenir-destination et photographies (en ligne) de quelques œuvres d’art : publics actuels du land art*. Christelle Proulx et Suzanne Paquet, Département d’histoire de l’art et d’études cinématographiques, Université de Montréal

Données: 
- [SunTunnels](https://observablehq.com/@artetsite/carte-sun-tunnels-5-photos-complet)
- [Broken Circle](https://gist.githubusercontent.com/artetsite/6e040a53d60d68215557bc2b2045e6b9/raw/4a2e31ba539f0ae6d33d5be908425add2b540b59/Broken%25202%2520photos%2520top%2520clean.csv)
- Lightning Field
- Images

CSS:
- [fichier CSS complémentaire](./artetsite.css) (pour les iframes)


### Nombre de vues - Sun Tunnels

<iframe width="100%" height="584" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/line-chart-fig2?cells=chart"></iframe>

Lien vers le [Notebook](https://observablehq.com/@artetsite/line-chart-fig2)

[Essai avec un diagramme de barres](https://observablehq.com/@artetsite/vues-sun-tunnels)


### Carte _Sun Tunnels_

<iframe width="100%" height="756" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos-complet?cells=styles%2Cchart%2Clegendaire"></iframe>

Problèmes et observations: 
- Palau: n'est pas un pays dans le fichier geojson employé
- choix des couleurs et des détails graphiques à valider
- implémentation avec SensPublic à tester


Essais précédents: 
- [Premier essai pour la carte](https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos-tests?cells=chart%2Clegendaire)
- [Essai deux: couleurs + légende](https://observablehq.com/embed/@artetsite/carte-sun-tunnels-5-photos?cells=chart%2Clegende)


### Carte _Broken Circle_

<iframe width="100%" height="581" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-broken-circle-2-photos?cells=chart%2Clegendaire"></iframe>

Lien vers le [Notebook](https://observablehq.com/@artetsite/line-chart-fig2)


### Carte _Lightning Field_ 

<iframe width="100%" height="581" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/carte-lightning-field-2-photos?cells=chart%2Clegendaire"></iframe>


Lien vers le [Notebook](https://observablehq.com/@artetsite/carte-broken-circle-2-photos)


### Production d'une nouvelle carte

Étapes: 
- _fork_ une carte qui fonctionne
- changer le titre
- changer l'url des données _Gist_
- changer l'url des images
- adapter l'échelle + choisir les couleurs


## Références

### Références Observable & D3.js

Couleurs
- Production de palettes de couleur: [coolors](https://coolors.co/)
- [Image color picker](https://imagecolorpicker.com)
- [Dégradés de couleurs D3.js](https://github.com/d3/d3-scale-chromatic)

Fonctionnement des échelles
- [Documentation D3.js](https://observablehq.com/@d3/continuous-scales)


### Outils utilisés

[D3.js](https://d3js.org/) dans de[Observable HQ](https://observablehq.com/@artetsite)

[Github](https://github.com/artetsite): 

- Gist pour les données (attention à bien mettre l'url du gist à jour en cas de changement)
- Page web en markdown, publiée avec Jeckyll et Github Pages

### Bibliographie

- [Mémoire](http://lenamk.site/memoire/) Lena Krause: en particulier le chapitre 3 pour les expérimentations avec des viusalisations interactives


## Inspiration

### Cartes

<iframe width="100%" height="1038" frameborder="0"
  src="https://observablehq.com/embed/@artetsite/pen-and-ink-stipple-effect?cells=test"></iframe>


<style type="text/css" rel="stylesheet" href="./artetsite.css">