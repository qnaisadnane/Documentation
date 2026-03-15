
#  EVALUATION JAVASCRIPT 

## SET A 

### Les Bases JavaScript

#### 1/ JavaScript est un langage de programmation interpreté , qui permet d'interagir avec l'utilisateur

#### 2/ les types de données primitifs c'est comme string , number , null , boolean ...
les types de données de références c'est comme objet , array

#### 3/
##### let : declare des variable qui sont accessible seulement dans les blocs et il ne sont pas accessible a l'exterieure du bloc , et il ne peut pas etre redeclare

 exemple : 
 {
 let a=2;
 }
//ne sera pas accessible ici

##### var : déclare un variable qui peut etre accessible dans son bloc et dans l'exterieur du bloc , et il peut etre redeclarer

exemple : 
var x = "adnane";
var x = 4;
 {
 var a=2;
 }
//il sera accessible ici

##### const : constante qui ne peut pas changer sa valeur

##### typeof : renvoie le type du variable

#### 4/ La différence entre === et == : 
=== : pour vérifier le type et la valeur
== : pour vérifier seulement la valeur
exemple : 5 === "5" c'est faux car "5" est un string
          5 == "5" c'est vrai car le type est negligeable

#### 5/ La différence entre for of et for in :
##### for of : pour récupérer les objets / les valeurs / les éléments
##### for in : pour récupérer les indices
exemple : 
const sports = ["foot" , "tennis" , "basket"];
    for(sport of sports){
    console.log(sport);
    }
    for(index in sports){
    console.log(index);
    }


 * on utilise const pour creer un constant qui ne peut pas etre changé

exemple : const nom = document.getElementbyId('id');

 * var pour un déclarer un variable globale

var x =3;
var x = 6;

if(true){
 var a = 3
}
 console.log(a);
(elle va s'afficher)
 * let pour déclarer un variable seulement dans les blocs

if(true){
 let a = 3
}
 console.log(a);
 (elle ne va pas s'afficher)
