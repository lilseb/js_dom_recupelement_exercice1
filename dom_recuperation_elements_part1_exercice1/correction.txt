//getElementByTagName

//1
let monTitre = document.getElementsByTagName('h1')
console.log(monTitre);

//2
let sousTitre = document.getElementsByTagName('h3')
console.log(sousTitre);
let firstSoustitre = sousTitre[0]
let secondSoustitre = sousTitre[1]
let threeSoustitre = sousTitre[2]

console.log(threeSoustitre);

//3
let para = document.getElementsByTagName('p')
console.log(para);
let secondPara = para[1]
console.log(secondPara);

//4
let allLi = document.getElementsByTagName('li')
console.log(allLi);

let threeLi = allLi[2]
console.log(threeLi);