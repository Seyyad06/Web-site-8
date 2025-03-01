let name = prompt("Adınızı girin:");
let age = parseInt(prompt("Yaşınızı girin:"));

if (age > 20) {
  console.log(name.toUpperCase());
} 

else {
  alert("Yaşınız azdır.");
}

if (age > 80) {
  console.log("qocalmisan");
}

let repeatedName = name + age;
console.log(repeatedName.repeat(age));
