Object Oriented programming (OOP) is a programming paradigm that relies on the concept of classes and objects.
It is used to structure a software program into simple, reusable pieces of code blueprints (usually called classes), which are used to create individual instances of objects.

Benifits of OOP:
1. Modularity for easier troubleshooting
- it's easier to find the bugs when it is in class.
2. Reuse of code through inheritance
- classes can be access through parent child inheritance. ex one of the colleague wanted to access the mustang object therefore he need to access the raceCar object to get object he wanted


Pseudocode with Description :
let names = {
    fname: "Dillion",
    lname: "Megida"
}
console.log(names.fname);
console.log(names.hasOwnProperty("mname"));

// Expected Output
// Dillion
// false
//The object variable names has only two properties - fname and lname . No methods at all.
//So where does hasOwnProperty come from?
//it comes from the Object prototype.

