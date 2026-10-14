# Metalex Soudure

Site vitrine de **Metalex Soudure** : soudure, ferronnerie et tuyauterie industrielle à Saint-Nicolas (Liège).
En ligne : https://crisfag.github.io/Metalex-soudure-/

Site statique (HTML + CSS + un peu de JavaScript, sans build), publié par GitHub Pages depuis `main`.

## Ajouter une réalisation
1. Déposer la photo dans `images/` (JPG, 1400 px de large maximum).
2. Dans `index.html`, section `#realisations`, copier un bloc `<figure class="tile">` et changer :
   - `src`, `width`, `height` et `alt` de l'image ;
   - `data-cat` : `garde-corps`, `portails`, `sur-mesure` ou `industrie` ;
   - la légende `<figcaption>`.
   Les compteurs des filtres se mettent à jour tout seuls. La réalisation s'ajoute au carrousel
   à l'endroit où le bloc est placé ; une photo en paysage peut prendre la classe `tile--wide`.

## Ajouter un avant / après
Déposer deux photos de même cadrage dans `images/avant-apres/` (`nom-avant.jpg`, `nom-apres.jpg`),
puis copier un bouton `<button class="ba-pick">` dans `index.html` (section `#avant-apres`)
en changeant `data-before`, `data-after`, leurs `alt`, `data-text` et le titre.

## Fil Facebook
Le fil de la page (`profile.php?id=61588205213844`) n'est chargé qu'après un clic du visiteur,
pour respecter le consentement aux cookies de Facebook.
