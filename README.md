# Introduction à Node.js

## De quoi s'agit-il ?

L'histoire de JavaScript est intimement liée à celle des navigateurs. JavaScript a essentiellement été créé pour ajouter de l'interactivité aux pages web. [Cet article](https://blog.alterway.fr/post/2016/02/05/2016-02-05-javascript-histoire-et-ecosysteme/) présente l'histoire du langage.

Pour bien comprendre l'intérêt de Node.js, et la différence entre Node.js et JavaScript dans le navigateur, voici quelques éléments de contexte.

D'abord, *tous* les langages, que ce soit C, C++, PHP, Java, JavaScript, existent au sein d'un "écosystème". Par là, on entend :

  * Le langage lui-même
  * Une "boîte à outils" lui permettant de faire quelque chose d'utile

Parmi les exercices qu'on donne aux débutants en programmation, la plupart sont destinés à se familiariser avec le langage :

  * ses types de données
  * ses structures de contrôle (`if/else`, `switch`, les boucles `for`, `while` et `do while`)
  * ses opérateurs
  * etc.

Puis on en vient à la "boîte à outils", qu'on nomme souvent "librairie standard" ou "API". Ce sont des fonctions livrées avec le langage. Par exemple, en JavaScript, que ce soit sous Node.js ou le navigateur, on a `console.log(...)` pour afficher quelque chose. Cela ne fait pas partie du *langage* lui-même, mais de ses "API".

Un deuxième exemple d'utilisation des API du langage, cette fois spécifique au navigateur. Ouvre un nouvel onglet, et colle ceci dans la console :

    document.write('<h1>Hello!</h1><button onclick=\'alert("Hello")\'>Click me</p>')

Tu devrais voir le contenu de l'onglet changer ! Ce simple exemple démontre deux capacités de JS dans le navigateur :

  1. manipuler à volonté le contenu de la page web, et
  2. réagir aux actions de l'utilisateur.