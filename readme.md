# Pseudo-éléments

Les pseudo-éléments sont utilisés pour ajouter du contenu ou des styles à un sélecteur de façon uniforme.

Par exemple, un client pourrait demander d'ajouter l'emoji 🔗 à tous les liens sur son site. Bien qu'il serait possible de manuellement copier/coller l'émoji partout, ceci consommerait du temps, comporterait un risque d'erreur et si de nouveaux liens étaient ajoutés par la suite, rien ne garantirait que la personne penserait à copier ledit émoji.

Heureusement, les pseudo-éléments peuvent aider!

::before & ::after{}
---------------------------------

Les pseudo-éléments `::before` et `::after` permettent d'ajouter du contenu à l'intérieur d'un élément via la propriété `content`.

Comme leurs noms l'indiquent:

*   `::before` ajoute un contenu au début ⬅️
    
*   `::after` ajoute un contenu à la fin ➡️
    

[CodePen | smnarnold 👀](https://codepen.io/smnarnold/pen/4a65e880ebe29e280021ee4bff323b24)

```À gauche, ::before.```  
```À droite, ::after.```

Remarquez comment le double deux points `::` sert à séparer le sélecteur de base de son pseudo‑élément.

Anciennement, il était possible d'écrire ses pseudo-éléments avec un seul `:`, comme les [pseudo-classes](/cours/css/pseudo-classes). Cependant, depuis l'arrivée de CSS3, cette pratique est désuète.

`::before` et `::after` acceptent les mêmes propriétés CSS qu'un sélecteur normal. Il est donc courant de les voir utilisés pour jouer un rôle similaire à celui d'un tag HTML normal.

Par exemple, il est possible d'afficher une image personnalisée via la propriété background-image plutôt qu'un texte/emoji.

[CodePen | smnarnold 👀](https://codepen.io/smnarnold/pen/c74ccfd271d3dc05ff9ed9ae79046f81)

_⚠︎ Erreur fréquente_

Lorsqu’un pseudo-element _(_`::before` _ou_ `::after`_)_ n’apparait pas, il s’agit généralement de la propriété `content` qui a été omise. Même si elle ne contient rien, sa présence est obligatoire pour qu’un pseudo-element affiche.

Ils sont aussi souvent utilisés en combinaisons avec les [pseudo-classes](/cours/css/pseudo-classes) et les [transitions](/cours/css/transition) afin de créer des effets de survole.

[CodePen | smnarnold 👀](https://codepen.io/smnarnold/pen/550cf312a5f562e09bc037729925c437)

*   [::before](https://developer.mozilla.org/fr/docs/Web/CSS/::before)
*   [::before](https://www.w3schools.com/cssref/sel_before.asp)
*   [::after](https://developer.mozilla.org/fr/docs/Web/CSS/::after)
*   [::after](https://www.w3schools.com/cssref/sel_after.asp)

Autres pseudo-éléments
-------------------------------------------------

Il existe évidemment d'autres pseudo-éléments. Cependant puisque leur usage est moins répandu. Nous ne nous attarderons pas.

[_En savoir plus_ Article MDN à propos des pseudo-elements.](https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-elements#Liste_des_pseudo-%C3%A9l%C3%A9ments)

🤫

Tous les icônes/émojis dans les boites de texte de ce site, comme la tête de dragon de MDN dans le bloc précédent, sont ajoutés avec des `::before`.

_Exercice_  
[Pseudo-éléments - Zab Café](/exercices/css/pseudo-elements-zab-cafe)

Pour cet exercice, vous devez compléter une page de blog du torréfacteur montréalais Zab Café ☕️ en la bonifiant avec des styles de liens...

   ![](/img/asset/YXNzZXRzL3BhZ2UtcHJldmlld3MvcHNldWRvLWVsZW1lbnRzLXphYi1hcGVyY3UucG5n?w=185&s=0275584969bcbfa8b3f9bc5104be58f3)

Résumé vidéo(#Résumé vidéo)
-----------------------------

[![](https://img.youtube.com/vi/e1KpKBHJOrA/0.jpg)](https://www.youtube.com/watch?v=e1KpKBHJOrA)
