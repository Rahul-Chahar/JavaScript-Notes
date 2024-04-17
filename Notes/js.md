#Hoisting
---
## 
getName();
console.log(x);

var x = 7;
function getName(){
    console.log("Namste JavaScript");
}

*output*
Namste JavaScript
Undifined
---
*Hoisting ki help se ham initialize karne se phele access kar skte hai for eg-> 
getName();
console.log(x);

ye baad mein initialize hue hai but hamne access phele hi kar liye*

