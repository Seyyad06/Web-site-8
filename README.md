index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
    <script src="./script.js"></script>
</html>




script.js
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
