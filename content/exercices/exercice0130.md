---
title: "0130 - Fonctions - pair ou impair"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer une fonction qui s'appelle "oddOrEven" :

- cette fonction prend un paramètre en entrée de type **number** ;
- cette fonction renvoie une chaine de caractères indiquant *"odd"* si le nombre passé en paramètre est impair, et *"even"* s'il est pair.

## Code

```javascript

//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let result = (oddOrEven(13) === "odd" && oddOrEven(12) === "even") ? "SUCCES : Vous avez réussi l'exercice ! Bravo." : "ERREUR : " ;
result += (oddOrEven(7) === "odd") ? "" : "La gestion des nombres impairs ne fonctionne pas ; "
result += (oddOrEven(6) === "even") ? "" : "La gestion des nombres pairs ne fonctionne pas ; "
console.log(result)

```
