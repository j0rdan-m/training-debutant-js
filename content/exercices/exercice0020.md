---
title: "0020 - Variables - String"
date: 2021-11-15T10:38:09+01:00
draft: false
---

## Objectif

Dans cet exercice, vous devrez créer trois variables :

- la variable 'hello' qui vaut "bonjour" ;
- la variable 'iamdev' qui vaut "Je développe en javascript" ;
- la variable 'intro' qui doit correspondre à la valeur de la variable 'hello' suivi d'une virgule, d'un espace, et enfin de la valeur de la variable 'iamdev' ;

## Code

```javascript

//AJOUTER VOTRE CODE ICI



// NE PAS TOUCHER AU CODE CI-DESSOUS

let str1 = (hello === "bonjour") ? true : false ;
let str2 = (iamdev === "Je développe en javascript") ? true : false ;
let str3 = (intro === "bonjour, Je développe en javascript");

if (str1 && str2 && str3){
    console.log("SUCCES : Vous avez réussi l'exercice ! Bravo.")
}else{
    console.error(`hello vaut "${hello}" et doit valoir "bonjour", iamdev vaut "${iamdev}" et doit valoir "Je développe en javascript" et intro vaut "${intro}" et doit valoir "bonjour, Je développe en javascript"`)
}

```
