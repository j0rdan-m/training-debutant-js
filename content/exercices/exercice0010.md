---
title: "Variables - Number"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer trois variables :

- la variable 'un' qui vaut 1 ;
- la variable 'deux' qui vaut 2 ;
- la variable 'vingttrois' qui vaut 23 ;

Chaque variable doit être un nombre, et pas une string

## Code

```javascript

//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let type = (typeof(un)!= 'number' || typeof(deux)!= 'number' || typeof(vingttrois)!= 'number') ? false : true ;
let value = (un === 1 && deux === 2 && vingttrois === 23)

if (!type){
    console.error("Vérifier que les variables sont bien des nombres")
    return 0;
}
if (!value) {
    console.error("Vérifier la valeur des nombres")
}

if (type && value){
    console.log("SUCCES : Vous avez réussi l'exercice ! Bravo.")
}

```
