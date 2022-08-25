# Le CSS
Les CSS (Cascading Style Sheets en anglais, ou « feuilles de style en cascade ») sont le code utilisé pour mettre en forme une page web. Les bases des CSS présentent ce qu'il faut savoir pour commencer. Nous répondrons à des questions comme : Comment rendre mon texte rouge ou noir ? Comment faire apparaître mon contenu à tel endroit de l'écran ? Comment décorer ma page web avec une image ou une couleur d'arrière-plan ?

## Donc, que sont les CSS, réellement ?
De la même façon que HTML, CSS n'est pas vraiment un langage de programmation. C'est un langage de feuille de style, c'est-à-dire qu'il permet d'appliquer des styles sur différents éléments sélectionnés dans un document HTML. Par exemple, on peut sélectionner tous les éléments d'une page HTML qui sont paragraphes et afficher leurs textes en rouge avec ce code CSS :

```css
p {
  color: red;
}
```

Analysons notre règle css. Dans notre précédent exemple nous avons en premier le sélecteur, c'est à dire sur quels éléments va s'appliquer le style.

Ensuite nous avons une déclaration qui est composée de la propriété (color) et de sa valeur (red) séparés par un deux points (:). On termine la déclaration par un point virgule (;).

Le sélecteur est suivi d'une ou plusieurs déclarations.

```css
p {
    color: red;
    font-size: 12px;    
}
```
