---
title: "0040 - Variables - boolean"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer trois variables :

- la variable 'bool1' qui sera un boolean vrai ;
- la variable 'bool2' qui sera un boolean faux ;
- la variable 'bool3' qui sera l'inverse de bool1;

## Code

```javascript


//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let error = ""
error += (bool1) ? "" : "bool1 doit valoir vrai ; ";
error += (!bool2) ? "" : "bool2 doit valoir faux ; ";
error += (bool3 === !bool1) ? "" : "bool3 doit valoir l'inverse de bool1";
let result = (bool1 && !bool2 && bool3 === !bool1) ? "SUCCES : Vous avez réussi l'exercice ! Bravo." : `ERROR : ${error}`; 
console.log (result)


```
