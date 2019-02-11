## **TP Responsive Web Design**

![](img/exemple.gif)

1. Ajouter [bootstrap](https://getbootstrap.com/docs/4.2/getting-started/download/) à votre projet

2. Centrer les éléments sur la page grace à un container Bootstrap

3. Utiliser la [grille](https://getbootstrap.com/docs/4.2/layout/grid/) fluide de Bootstrap pour définir la largeur des éléments :

   - Menu
   - Partie principale

4. Utiliser les classes de grille (col-xs-_ / col-md-_ etc.) pour afficher successivement les albums par 6 sur grand écran, 4 pour les tablettes et 2 en dessous

5. Utiliser Bootstrap pour :

   - Masquer la colonne de gauche sur mobile et sur tablette en mode portrait ([display utilities](https://getbootstrap.com/docs/4.2/utilities/display/))
   - Aligner les liens Collection et History à droite lorsque l'espace disponible devient insuffisant
   - Mettre en place le [menu déroulant](https://getbootstrap.com/docs/4.2/components/dropdowns/) (en haut à droite)

6. Remplacer toutes les tailles de police en pixel par des unités relatives (em ou rem)

7. Régler le viewport pour les mobiles

```html
<meta
  name="viewport"
  content="width=device-width, initial-scale=1.0, shrink-to-fit=no"
/>
```

Cela permet d'eviter que l'utilisateur zoom dans votre page web pour naviguer

8. Utiliser les **medias queries** pour :

   - Masquer le champs de recherche lorsque l'espace disponible devient insuffisant
   - Masquer les icônes twitter et facebook sur mobile
   - Ajuster la taille du texte aux 3 points de ruptures suivants : 1400px (grossir) / 600px (plus petit) / 450px (encore plus petit)

9. Redimensionner la fenêtre du navigateur ou émuler la taille du device à travers la console dévelopeur. Tester que la page est visuellement cohérente à toutes les résolutions. Faire les ajustements nécessaires avec les media queries

10- la suite du tp se trouve [ici](https://github.com/clementAC/Tp5-Responsive-web-design-react)
