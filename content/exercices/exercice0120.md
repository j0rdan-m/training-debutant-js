---
title: "0120 - Fonctions - inverser un boolean"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer une fonction qui s'appelle "invertBoolean" :

- cette fonction prend un paramètre en entrée de type **boolean** ;
- cette fonction renvoie un tableau contenant un premier item qui est un boolean qui vaut l'inverse du boolean d'entrée ;
- si le boolean d'entrée est vrai, le second item du tableau est une string dont la valeur est *"C'était VRAI"*, 
- sinon, le second item du tableau est une string dont la valeur est *"C'était FAUX"*

## Code

```javascript

//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let answer1 = invertBoolean(true)
let result1 = (!answer1[0] && answer1[1] === "C'était VRAI") ? true : false;
let answer2 = invertBoolean(false)
let result2 = (answer2[0] && answer2[1] === "C'était FAUX") ? true : false;

let result = (result1 && result2) ? "SUCCES : Vous avez réussi l'exercice ! Bravo." : "ERREUR : "
result += (!answer1[0]) ? "" : "l'inversion d'un boolean vrai ne fonctionne pas ; "
result += (answer2[0]) ? "" : "l'inversion d'un boolean faux ne fonctionne pas ; "
result += (answer1[1] === "C'était VRAI" && answer2[1] === "C'était FAUX") ? "" : "Attention aux textes attendus."

console.log(result)

```
