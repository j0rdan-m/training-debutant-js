---
title: "0110 - Fonctions - construction de chaine"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer une fonction qui s'appelle "buildStr" :

- cette fonction prend deux paramètres en entrée : le *prénom d'une personne* et son *âge* ;
- cette fonction renvoie une chaine de caractère reprenant le prénom de la personne, suivi de " a ", suivi de l'âge, suivi de " ans." ;

## Code

```javascript

//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let strTest = buildStr("j0rdan", 38);
let result = (strTest === "j0rdan a 38 ans.") ? true : false ;

if (result){
    console.log("SUCCES : Vous avez réussi l'exercice ! Bravo.")
}else{
    console.error(`ERREUR : "${strTest}" est différence de "j0rdan a 38 ans." et la fonction doit être modifiée.`)
}

```
