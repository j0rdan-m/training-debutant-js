---
title: "Exercices JS"
date: 2021-11-15T10:38:09+01:00
draft: false
---

# training-debutant-js
Exercices pour débutant

## Ajouter un exercice

Pour ajouter un exercice, merci de créer un fichier "exerciceN" dans le dossier content/exercices, et de reproduire le modèle suivant : 

````md
---
title: "Variables - Number"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans ce premier exercice, vous devrez créer trois variables :

- la variable 'un' qui vaut 1 ;
- la variable 'deux' qui vaut 2 ;
- la variable 'vingttrois' qui vaut 23 ;

Chaque variable doit être un nombre, et pas une string

## Code

```javascript

// NE PAS TOUCHER AU CODE CI-DESSOUS

let var1 = !isNaN(un) ? true : false;
let var2 = !isNaN(deux) ? true : false;
let var23 = !isNaN(vingttrois) ? true  : false ;

if (var1){
    let result1 = (un === 1) ? true : false ;
    if (!result1) {
        console.error("Le résultat de la variable 1 est erroné")
    }
}else{
    console.error("la variable 'un' n'est pas un nombre")
}

if (var1 && var2 && var23){
    console.log("SUCCES : Vous avez réussi l'exercice ! Bravo.")
}

```

````