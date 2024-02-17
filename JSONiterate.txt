For the given JSON iterate over all for loops (for, for in, for of, forEach)

let student = {
  name : 'Assay'
  age : '29'
}


(OR)

let person = { };
person.firstname = "Assay"
person.age = "29"

console.log('loops in objets')
for (let prop in person) {
  console.log('${prop}=${person[prop]}')
//click on RUN button
//loops in objects
//firstname=Assay
//age=29

The ‘For In’ Loop
Looping through an Object Property
var person = {
   fistName: "Assay",
   lastName: "Sooraj",
   age: 29
}; 
for (let x in person) {
   console.log(x + ": "+ person[x])
}


The For Of () Loop
var mycars = [{name:'Assay'}, {name:'i20'}];
for (var car of mycars) 
{
  document.write(car.name + "<br />");
}

The ForEach() Loop
var names = ["Assay", "Sooraj", "Lilly", "Sajitha", "Babu"];
names.forEach(function1);
function function1(currentValue, index) {
   console.log("Index in array is: "+index + " ::  Value is: "+currentValue);
}
‍
